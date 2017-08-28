# spring_ioc  
Spring bean 如何解决循环依赖：  
1.构造器循环依赖 无法解决
2.Setter注入 通过提前暴露完成构造器注入但问完成其他步骤的bean
