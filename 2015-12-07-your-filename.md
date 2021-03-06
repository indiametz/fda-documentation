---
title: Housekeeping
tags: 
  - formatting
keywords: "housekeeping, housekeeping status, housekeeping rules"
last_updated: "December 7th, 2015"
summary: Labels are just a simple Bootstrap component that you can include in your pages as needed. They represent one of many Bootstrap options you can include in your theme.
published: true
---




#**Housekeeping**  

The Housekeeping section in your Frontdesk Anywhere helps you set up certain rules to govern the change in housekeeping status for each room at your property. This is necessary, in turn, to define what your Housekeeping Team will need to: in other words, you will be able to define in what occasions the system should report a certain room to be 'dirty' or 'clean', thus making it easier for the housekeepers to know what action is required of them!

##**Housekeeping Status**    

Housekeeping Statuses serve to indicate whether a certain room needs attention from your Housekeeping staff or not. Frontdesk Anywhere performs changes in the Housekeeping Status of each room thanks to certain Rules you will have to set up: since the rules are based on the Housekeeping Statuses, it will be good for you to familiarize with what each status mean!  

  - In the Admin Settings, click on the blue link **Housekeeping Statuses** under section _Housekeeping_:  
  
  ![](1.png]({{site.baseurl}}/images/1.png)  
  
  - You will see a list of available Housekeeping Statuses:  
  
  ![](2.png]({{site.baseurl}}/images/2.png)  

Here is a breakdown of what they mean:  

1. **Clean**: Room is clean and ready to be rented!  

2. **Inspect**: Room needs a formal inspection, where action from an Housekeeper might or not be necessary.  

3. **Dirty**: Room is currently rented but needs action from Houssekeepers.  

4. **Dirty Vacant**: Room is not currently rented, it needs full operations from housekeeping.  


**NOTE**: It is currently not possible to add or edit an Housekeeping Status.  


##**Housekeeping Rules**  

Housekeeping Rules are necessary to establish how the system should use the Housekeeping Status. Since the work of your Housekeeping staff will center on the Statuses, it is extremely important to set your rules correctly!  

 - In the Admin Settings, click on the blue link **Housekeeping Rules**, under section _Housekeeping_:  
 
 ![](3.png]({{site.baseurl}}/images/3.png)  
 
 - Your Frontdesk Anywhere comes with some very common default rules that define how your Housekeeping Statuses are to change:  
 
 ![](4.png]({{site.baseurl}}/images/4.png)  
 
 - Before trying to create a new rule, let us examine what each default rule does:  
 
 1.**Check-In - Dirty**:  this rule is triggered by the change in the reservation status. When the reservation status will change to _Checked-In_, that will cause the Housekeeping Status of the room to also change, in this case to _Dirty_.  
 
 
 2.**Check-Out - Dirty Vacant**: this rule is also triggered by the change in reservation status. In this case, when a reservation status is set to _Checked-Out_, the Housekeeping Status will in turn change to _Dirty Vacant_.  
 
 
 3.**Nightly - Dirty**: differently from the previous two rules, this one is not triggered by changes in reservation status, but it is triggered automatically on a nightly basis. This rule establiushes that any checked-in room will be marked with the Housekeeping Status _Dirty_, regardless of whether the status of a reservation has been changed on that day: in hotel management words, this rule accounts for your Stay Overs.  
 
 
 4.**Room Change - Inspect**: if any of your guests changes room during their stay, the system will trigger the previous room to an 'Inspect' Housekeeping Status.  
 

- To **Add** an Housekeeping Rule, click on the blue button _Add_ at the bottom of the rule list:  

![](5.png]({{site.baseurl}}/images/5.png)  

- You will need to fill in all information. Begin by giving the rule an easily recognizable title, and if applicable, a short description. From the scroll down menu _Housekeeping Status_, select the housekeeping status you want your rooms to have, after the rule has run:  

![](6.png]({{site.baseurl}}/images/6.png)  

- By clicking on the right circle box, select whether you want the rule to be triggered by changes in the Room Status, or whether you want the rule to run on nightly basis: in the latter case, the rule will run automatically every night.  
You can also choose the rule to be triggered by a specific event (check-in/out day) or by days of the week: in the latter case you will need to specify what day/s of the week you want the rule to run, by clicking on the check-boxes:  

![](7.png]({{site.baseurl}}/images/7.png)  

 - Choose the folio status where the rule is to apply:  
 
 ![](8.png]({{site.baseurl}}/images/8.png)  
 
 - In the  _Stay Interval_ editable box, select the interval you want the rule to run for (interval of 2 days or 3 days, etc.); also, choose whether you want the rule to repeat on a regular basis by checking the box under _Repeat_:  
 
 ![](9.png]({{site.baseurl}}/images/9.png)  
 
 - From the scroll down menu, select whether you want the rule to have a lower or higher priority, by choosing the right option:  
 
 ![](10.png]({{site.baseurl}}/images/10.png)  
 
 - Finally, choose whether the rule is to be applied to all reservations or whether you want to manually apply the rule in each reservation folio; place the priority the rule should have, check the _Statu_ box to make it active, and click on the blue button _Save_ when finished:  
 
 ![](11.png]({{site.baseurl}}/images/11.png)  
 
 
 You will see your Housekeeping Rules and Statuses in action by going in the _Housekeeping_ tab on top of your Tape Chart:  
 
![12.png]({{site.baseurl}}/images/12.png)




