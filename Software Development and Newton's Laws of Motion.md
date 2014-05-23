# Intro 
I have no idea since when the word **velocity** found a new home in software development, it is nevertheless popular these days. However I am pretty sure that Mr Isaac Newton would not be happy if you talk about **motion** without mentioning his laws. 

# First Law
> When viewed in an inertial reference frame, an object either remains at rest or continues to move at a constant velocity, unless acted upon by an external force.

A team/product is either dead (therefore remains at rest) or is moving at a constant velocity (let's say generating certain amount of revenue or eating certain amount of buget per day). Here come the external forces 

  - developers are fixing bugs 
  - developers are adding new features 
  - developers are introducing more bugs (lol)
  - business requests to cut down the operation cost 
  - third party competition is changing the market 
  - users are changing
  - this list goes on and on 
  
Now I declare, it is against the law to talk about team **velocity**, because what should you do to **maintain** the team's velocity? Nothing, you should do **nothing**! 

Well that will upset most of the managers, "I'd rather my developers do **something**". 

So we need another law. 

# Second Law
> F = ma. The vector sum of the forces F on an object is equal to the mass m of that object multiplied by the acceleration vector a of the object.

**Acceleration** is the ability to change the velocity. The **F** is treated as a constant here, because, come on, let's be honest, your team is pretty much fixed size, unless you are Google. Your time is pretty much fixed to 24 hours  per day unless you live on Mars which is 24.622962 hours to be exact. Now we are screwed ... there is only one variable left to play. According to second law, for a given force F, the acceleration is inversely proportional to the mass.  Mass is the burdern, it is going **against** acceloration. 

Here is a short list of how to gain some mass
  
  - too many good-to-have features 
  - too much technical debt
  - too many abstractions, layers upon layers, ORM, DAO, service, controller, view. We need all of them to get some trivial {"user_id": 123} out of that database. oh forget to mention, there is SQL, and NoSQL ... 
  - too many processes 
  - too many patterns, EnterprisyStrategyFactoryBuilderAdapterListenerInterceptor
  - too many communication delegations, business -&gt; project manager -&gt; business analyst -&gt; team leader -&gt; developer (add more roles at your own will)
  - too many frameworks. JavaEE, Spring, Hibernate, Struts, Bootstrap, jQuery, Angular.js, Ember.js. Dare to lookup JavaEE? There are **39** JSRs listed under JavaEE7!
  - too many servers. Web servers, relational database servers, NoSQL servers, cache servers, message queue servers, third party integration servers ... 

Ye in the end you do want to make a change, do you? Here comes the other law

# Third Law 
> To every action there is always opposed an equal reaction: or the mutual actions of two bodies upon each other are always equal, and directed to contrary parts.

A: "Can we remove feature XYZ? so that the codes can be greatly simplified"<br/> 
R: "Please no, that is Shareholder ABC's favorite" <br/>
A: "Ooookie, nvm"<br/><br/>

A: "Can we change to git?"<br/>
R: "Nah, zip and email is our best friend" <br/>
A: "Maybe next time"<br/><br/>

A: "Can we upgrade java 1.4?"<br/>
R: "There are too many servers in prodution"<br/>
A: "Fine, let's stick to manual casting"

Aaaaah, I still want to type some more words but there is an equal reaction preventing me from doing that ... So let's call this a day.

Thanks for wasting your time reading my rants. 

**Happy Coding ...**

<hr/>

Reference 

* http://en.wikipedia.org/wiki/Velocity_(software_development)
* http://en.wikipedia.org/wiki/Newton's_laws_of_motion
