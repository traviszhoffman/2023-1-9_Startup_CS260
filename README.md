# 2023-1-9_Startup_CS260
Startup Application for CS260
Startup will be a web based project. Need to work on ideation but should have an idea soon.
2nd edit to it using github.
4th edit to create merge conflict muhaha.3rd edit using github.
Knowing how to resolve merge conflicts is very important and I'm glad for the refresher.

![image](https://user-images.githubusercontent.com/94704493/224210058-1c22ca4f-9168-46dd-899c-a67a04024062.png)
Have you wanted to keep track of your customers needs, remind them about apointments, and see when traffic was the busiest? But have you been worried that you aren't tech savvy enough or skilled enough to use such a tool? CRM for small to medium buisness designed to help them make data driven decions in regarding as well as using the twillio api to automatically send apointment reminders, review reminders, as well as other surveys but in a realatively simple way that anyone could understand and use.

Key Features:

Automated Apointment Reminders Using Twillio Api  
Be able to see what days are you busiest  
Real time updates  
Determine when customers don't show up and potentially why  
Results are persitently stored  
Ability to send custom deal messages to customers based on previous purchases  

Notes:  
WEB SERVERS:

Domain names are converted to IP address by doing a lookup in the Domain Name System (DNS). You can look up the IP address for any domain name using the dig console utility.  
determine the hops in a connection using the traceroute
top of tcp layer is application layer  

Layer	Example	Purpose  
Application	HTTPS	Functionality like web browsing  
Transport	TCP	Moving connection information packets  
Internet	IP	Establishing connections  
Link	Fiber, hardware	Physical connections  

curl to make http request  
microservices to develop and mange independetly  
serverless automatically 	

EC2	Server	t3.nano $0.0052 an hour ($3.50/month), t3.micro $0.0104 an hour ($7.00/month), t3.small $0.0208 an hour ($14.00/month)  
EC2 Elastic IP	Keep your IP address between reboots	First one is free if you keep it associated with a running server. $0.0052 an hour otherwise.  
Route 53	Domain name	$3/year for click TLD. More for others  
Route 53	DNS records	$0.50 a month for each root domain  

ssh secure shell
chmod change mode  
 Secure Hypertext Transport Protocol (HTTPS)., caddy acts as gateway,  The name server (NS) record contains the names of the authoritative name servers that authorize you to place DNS records in this DNS server, The start of authority (SOA) record provides contact information about the owner of this domain name.Route 53 is the AWS service that handles everything DNS related., subdomains, whois, 

 Every DNS server in the world references a few special DNS servers that are considered the authoritative name servers for associating a domain name with an IP address.

The DNS database records that facilitate the mapping of domain names to IP addresses come in several flavors. The main ones we are concerned with are the address (A) and the canonical name (CNAME) records. An A record is a straight mapping from a domain name to IP address. A CNAME record maps one domain name to another domain name. This acts as a domain name alias. You would use a CNAME to do things like map byu.com to the same IP address as byu.edu so that either one could be used.

![image](https://user-images.githubusercontent.com/94704493/224237343-b40fe10b-5f53-4d8f-b3e8-8189322a9fe3.png)
![image](https://user-images.githubusercontent.com/94704493/224237374-62a75a0e-d118-48f4-91e9-085b1f5b5b60.png)
![image](https://user-images.githubusercontent.com/94704493/224237455-a93d1cb6-2443-4342-bd71-3a5f7d62f1fa.png)
![image](https://user-images.githubusercontent.com/94704493/224237473-222257b6-8cde-4797-88e0-5cd0fe037c95.png)
![image](https://user-images.githubusercontent.com/94704493/224237693-b2baf21f-bd0f-4d59-abc2-d8ca9ded282b.png)
![image](https://user-images.githubusercontent.com/94704493/224237754-139c1809-519f-4a07-9860-9d1ab5db37ad.png)
![image](https://user-images.githubusercontent.com/94704493/224237811-32abd523-d4b7-4c68-b2ed-363457b740bd.png)
![image](https://user-images.githubusercontent.com/94704493/224238008-56921c83-a332-42b8-9cf5-5068ab1550d2.png)
![image](https://user-images.githubusercontent.com/94704493/224238091-a157d1af-ebaf-4a54-aa22-b08cb92cd578.png)
![image](https://user-images.githubusercontent.com/94704493/224238129-4775c682-4776-46ed-ab59-cbab40f46b22.png)
![image](https://user-images.githubusercontent.com/94704493/224238186-cda0ffbf-3ed6-4fe1-af6e-5298d5da842d.png)
![image](https://user-images.githubusercontent.com/94704493/224238252-6144a518-f55a-4aa6-802a-d5cc61d71f8f.png)
![image](https://user-images.githubusercontent.com/94704493/224238311-d4878bef-2762-40d5-be62-34838ac15cf0.png)
svg canvas
![image](https://user-images.githubusercontent.com/94704493/224238517-f2866011-f832-4836-b259-5745b927dadc.png)
element selectors, cobinators ex section h3
![image](https://user-images.githubusercontent.com/94704493/224238718-91c6af04-6cc3-4f33-b4d7-c05fddc9e499.png)
![image](https://user-images.githubusercontent.com/94704493/224238758-777c7e17-eda5-4352-88de-351738122890.png)
![image](https://user-images.githubusercontent.com/94704493/224238783-9d823d96-a0a7-457a-86e6-57ac1f62912f.png)
![image](https://user-images.githubusercontent.com/94704493/224238889-41d52a88-42dc-47b4-b40b-39753ba6f7ed.png)
![image](https://user-images.githubusercontent.com/94704493/224238913-6baef2bf-2da2-4414-935f-f8e8f3dc7b02.png)
![image](https://user-images.githubusercontent.com/94704493/224238950-c839e74b-8808-4331-be8d-6c2acd3f1609.png)
viewpor-t meta tag, float, flexbox, media queries,,tailwind, bootstrap,


** Midterm Review **

	1. Div creates a division element
	2. To point to another dns record you should use Cname(are alials)
		a. To put to an ip adress use an a record
	3. @import url("and then the fonts)
		a. Look up syntax to load
	4. Finally always gets called, Burger,Fries, taco, shake, noodles, 
		a. Java script promise being asychronous
		b. Not resolved till time out, and call back function doesn’t happen untill after
	5. Valid json {"x":3}
		a. Key value is always in qoutes
	6. Div.header { color: blue;} is the correct one
	7. Not valid there is no <javascript>1+1
		a. Valid script script src div onclick
	8. Filter function uses regex (/A|f/i) /I makes case not matter
	9. Not valid function f(x) = {}
	10. Padding puts space aroundd the content of selected elements
		a. Peanut butter maynoasi
		b. Pals before marriage
	11. Margin, boarder, padding , content
		a. Starting on the outsize going in
	12. Reducce function,map, filter,sum remember all these
		a. Reduces to one value
	13. Html tag for an undordered list
		a. Ul
	14. Adds a mouseoever event listner to a p element
	15. <a href> for links
	16. Map function
	17. Dom text content property sets the child text for the an element
	18. Chmod
	19. Sudo
	20. Ls -la
	21. Ssh

