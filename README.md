gradle -v
执行任务：gradlew clean
查看所有子工程：gradlew projects
查看所有任务：gradlew tasks
升降级gradle：gradlew wrapper --gradle-version 6.4
gradlew clean -q
DSL：Domain Specific Language：领域专用语言
闭包：开放匿名的代码块，可以接受参数，具有返回值，也可以被分配给变量
Android的配置就是自定义DSL
gradlew :router-gradle-plugin:uploadArchives，发布插件：router-gradle-plugin