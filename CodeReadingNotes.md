


## 消息发送关键类
* org.jetlinks.core.defaults.DefaultDeviceMessageSender
* org.jetlinks.core.message.FunctionInvokeMessageSender


## 规则引擎

### 核心概念映射的类
* org.jetlinks.rule.engine.api.model.RuleModel
* org.jetlinks.rule.engine.api.model.RuleLink
* org.jetlinks.rule.engine.api.model.RuleNodeModel
* org.jetlinks.rule.engine.api.model.Condition
* org.jetlinks.rule.engine.cluster.RuleInstance
  
* org.jetlinks.rule.engine.api.task.Task
* org.jetlinks.rule.engine.api.scheduler.Scheduler
* org.jetlinks.rule.engine.api.scheduler.ScheduleJob
  org.jetlinks.rule.engine.api.scheduler.SchedulingRule

### 框架
* org.jetlinks.rule.engine.api.RuleEngine

### 执行器
* org.jetlinks.rule.engine.api.task.TaskExecutor
* |-> org.jetlinks.rule.engine.defaults.FunctionTaskExecutor

### 数据流
* org.jetlinks.rule.engine.api.RuleData