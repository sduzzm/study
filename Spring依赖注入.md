# Spring依赖注入方案 #
## 自动装配（推荐） ##
组件扫描：
@Component 声明Bean
@ComponentScan 启用组件扫描
自动装配：
@Autowired

## Java配置 ##
应用场景：将第三方库中的组件装配到自己的应用中时，无法添加@Component注解
创建JavaConfig配置类
@Configuration：表明该类是一个配置类
@Bean：表明要注册为Spring上下文中的Bean

## XML配置 ##
<beans>
	<bean id="" class="">
	</bean>
</beans>