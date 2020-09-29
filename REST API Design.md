**Representational State Transfer (REST)**


# Advantage compare with SOAP

## SOAP(Simple Object Access Protocol)
Web Services 是一个可以将应用程序变为web应用程序，将自己本地的应用程序信息通过网络，发布到网络当中，让别人通过浏览器等访问本地的信息。
SOAP 是定义访问Web Services 的协议，也就是哪些是可以访问的，怎样的格式才能够访问，返回的格式又是什么样的，这些都是SOAP定义的。SOAP，作为传输层，用来在消费者和服务提供者之间传送消息。SOAP是Web服务的默认机制，其他的技术为可以服务实现其他类型的绑定。
WSDL 是描述SOAP协议的具体语言，用WSDL实现SOAP协议，把它写成文件，直接访问。WSDL用来描述服务；
UDDI，是把这些web services 收集和存储起来，这样当别人访问这些信息的时候就从UDDI中查找，看有没有这个信息存在。UDDI用来注册和查找服务；

用户可以在UDDI注册表（registry）查找服务，取得服务的WSDL描述，然后通过SOAP来调用服务。

## Compare

|      Topic      |                                                                                                                             SOAP                                                                                                                              |                                                                                                                                                             REST                                                                                                                                                              |
| :-------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|     Concept     |                                                                                   Makes data available as services (verb + noun),<br> for example “getUser” or “PayInvoice”                                                                                   |                                                                                                                          Makes data available as resources (nouns), for example “user” or “invoice”                                                                                                                           |
|      Pros       | Follows a formal enterprise approach Works on top of any communication protocol, even asynchronously <br> Information about objects is communicated to clients. <br>Security and authorization are part of the protocol.<br>Can be fully described using WSDL | Follows the philosophy of the Open Web<br>Relatively easy to implement and maintain<br>Clearly separates client and server implementations<br>Communication isn’t controlled by a single entity<br>Information can be stored by the client to prevent multiple calls.<br>Can return data in multiple formats (JSON, XML etc.) |
|      Cons       |                                                                    Spends a lot of bandwidth communicating metadata<br> Hard to implement and is unpopular among Web and mobile developers                                                                    |                                                                                                              Only works on top of the HTTP protocol <br> Hard to enforce authorization and security on top of it                                                                                                              |
|   When to use   |                                                          When clients need to have access to objects available on servers <br> When you want to enforce a formal contract between client and server                                                           |                                                                                            When clients and servers operate on a Web environment<br> When information about objects doesn’t need to be communicated to the client                                                                                             |
| When not to use |                                                                            When you want the majority of developers to easily use your API <br>When your bandwidth is very limited                                                                            |                                                                                               When you need to enforce a strict contract between client and server<br>When performing transactions that involve multiple calls                                                                                                |
|    Use cases    |                                                                                             Financial services<br>Payment gateways<br>Telecommunication services                                                                                              |                                                                                                                       Social media services<br>Social networks<br>Web chat services<br>Mobile services                                                                                                                        |
|     Example     |                                                                                                        https://www.salesforce.com/developer/docs/api/                                                                                                         |                                                                                                                                https://dev.twitter.com/<br>https://developer.linkedin.com/apis                                                                                                                                |
|   Conclusion    |                                                               Use SOAP if you are dealing with transactional operations and you already have an audience that is satisfied with this technology                                                               |                                                                                                                Use REST if you’re focused on wide-scale API adoption or if your API is targeted at mobile apps                                                                                                                |

# Best practices
## Use nouns for resources and not verbs
Always use plural nouns for consistency.

```
GET parts/1 
GET orders/123 
GET seats?id=3
```

## Never release an API without a version
Maintain at least one version back

## Partial response
Use fields to define optional parameters to be returned. 
```
/joe.smith/friends?fields=id,name,picture
```

## Error handle
| Category |                                                Description                                                |
| :------: | :-------------------------------------------------------------------------------------------------------: |
|   1xx    |                      Informational Communicates transfer protocol-level information                       |
|   2xx    |                   Success Indicates that the client’s request was accepted successfully                   |
|   3xx    | Redirection Indicates that the client must take some additional action in order to complete their request |
|   4xx    |               Client Error This category of error status codes points the finger at clients               |
|   5xx    |                 Server Error The server takes responsibility for these error status codes                 |
