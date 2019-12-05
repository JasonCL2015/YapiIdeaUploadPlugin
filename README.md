### 说明
基于YapiIdeaUploadPlugin 插件基础上，进行二次开发扩展，支持swagger 注解

支持右键项目一键同步Controller文件接口

支持dto mock配置，@ApiModelProperty(example="@mock")


### 使用方式：
.idea/misc.xml 文件中 添加以下配置
````
<!--yapi配置-->
<component name="yapi">
  <option name="projectToken">yapi项目token</option>
  <option name="projectId">项目id</option>
  <option name="yapiUrl">http://yapi.xxxx.com</option>
  <option name="projectType">api</option>
</component>
````