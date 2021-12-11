## Module 1 - Introduction

### Client-Server Model

In computing, a client can be a web browser or desktop application that a person interacts with to make requests to computer servers.
A server can be services such as Amazon Elastic Compute Cloud (Amazon EC2), a type of virtual server.

For example, suppose that a client makes a request for a news article, the score in an online game,
or a funny video. The server evaluates the details of this request
and fulfills it by returning the information to the client.

> If we already have a standard notion in computing, then why AWS or move to Cloud?

This principle makes sense when you run a cafe.
Employees are only paid when they're in the store working.
If Alice and John have taken time-off, well then they don't get paid.
The store owner simply decides how many baristas are needed and then just pays for the hours they work.
For example, the cafe is about to release a new drink, the New Years Special Drink.
In anticipation of this launch, you could always staff your shop with another complementary food item all day long,
just in case you suddenly get an unexpected rush at some point in the day.
Apparently, for most of the day, we don't have near enough customers to justify
paying for all those employees.

And yet, this is exactly what happens in an on-premises data center.
**You can't just snap your fingers and triple your capacity.**
When the business is hosted in cloud,
you don't pre-pay for anything. And you don't have to worry about capacity constraints.

When you need instances, you just click a button, and you have them.
And when you don't need them, another click, and they go away, and you stop paying for them.
The same way you don't pay for employees for hours that they're not working.

> In short, it's a pay-as-you-go approach.

### Cloud Computing

Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing.
On-demand delivery indicates that AWS has the resources you need, when you need them.
You don't need to tell the cloud provider in advance that you're going to need them.
Suddenly you find yourself needing 300 virtual servers. It is just a few clicks away where you scale up the system as you go.

#### Deployment models for cloud computing

When selecting a cloud strategy, a company must consider factors such as required cloud application components, preferred resource management tools, and any legacy IT infrastructure requirements.

The three cloud computing deployment models are cloud-based, on-premises, and hybrid.

1. **Cloud-Based Deployment**

   In a cloud-based deployment model, you can migrate existing applications to the cloud, or you can design and build
   new applications in the cloud.
   You can build those applications on low-level infrastructure that requires your IT staff to manage them.
   Alternatively, you can build them using higher-level services that reduce the management, architecting, and
   scaling requirements of the core infrastructure.

   For example, a company might create an application consisting of virtual servers, databases,
   and networking components that are fully based in the cloud.


2. **On-Premises Deployment**

   On-premises deployment is also known as a **_private cloud deployment_**.
   In this model, resources are deployed on premises by using virtualization and resource management tools.

   For example, you might have applications that run on technology that is fully kept in your on-premises data center.
   Though this model is much like legacy IT infrastructure, its incorporation of application management and
   virtualization technologies helps to increase resource utilization.


3. **Hybrid Deployment**

   In a **_hybrid deployment_**, cloud-based resources are connected to on-premises infrastructure.
   You might want to use this approach in a number of situations.
   For example, you have legacy applications that are better maintained on premises, or government regulations require your business to
   keep certain records on premises.

   For example, suppose that a company wants to use cloud services that can automate batch data processing and analytics.
   However, the company has several legacy applications that are more suitable on premises and will not be migrated to the cloud.
   With a hybrid deployment, the company would be able to keep the legacy applications on premises
   while benefiting from the data and analytics services that run in the cloud.