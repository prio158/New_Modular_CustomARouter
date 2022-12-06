# New_Modular_CustomARouter
基于ARouter开发一款的Router的框架

组件化：模块之间没有任何依赖，彼此还可以通信

![image](https://user-images.githubusercontent.com/72843017/205787466-f8da6d38-c7bd-4ee7-8cf7-26a0e92a8515.png)

1、ARouter注解：被ARouter注解的类在编译期通过APT技术，生成一个HashMap，key为group,value为RouterBean的集合
  
2、RouterBean：是一种数据类型，路由路径Path的最终实体封装类，它里面会携带被ARouter注解的类的grouop、path、类信息。
  
3、Parameter注解：用于界面跳转时传参。  
  

![image](https://user-images.githubusercontent.com/72843017/205787522-d3e5761b-3da1-45bf-8e13-22ae78889b46.png)

![image](https://user-images.githubusercontent.com/72843017/205787544-8de2a27d-f40f-43d7-9bfb-209e7e3143f5.png)

![image](https://user-images.githubusercontent.com/72843017/205787569-4e3400d0-d39b-4ec9-998c-37d4d6bce129.png)


