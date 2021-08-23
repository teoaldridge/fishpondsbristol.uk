# fishpondsbristol.uk
This is the first website I made independently, using HTML, CSS and Bootstrap. It serves my local park, community garden and a local community hall which hosts classes and other events.

!!! I could not upload all the files of this website on github because they are too big. 
Therefore I only uploaded the files of the portal page. 

You can visit the website here: 
## https://www.fishpondsbristol.uk/

The site is hosted on Infinity Free (a free hosting platform). 


## Here is my "Reflections Log" on making this website: 

•	The whole project took about three months, but that is, with about an hour of work per day. 

•	I suggested to a local organization to make a website for them. I was making it for free, but it was a good experience and something to add to my portfolio. 

•	First big issue was how to structure it. It was going to be one website for two organizations, a park and a community hall. 

•	I met with the chair of the two organizations and together we decided on a structure. The structure had the user’s perspective in mind- make things easy for users to find. 


•	Issue with choosing a domain name for the website. In the end chose fishpondsbristol.uk -points to the location, with two subdomains:
Hillfieldspark.fishpondsbristol.uk
Beechwoodclub.fishponndsbristol.uk – almost addresses 😊 
Chose the names of the places because this is what people are likely to know and search.

•	Making the site was tricky in some ways because there were a lot of clients involved: all the tutors in the hall, all the members of the organizations having ideas about how the site should look, structure, name of domains, etc. I needed articles from different people for the content, and I had to wait for all of them to send me their input. Sometimes I had to halt the making of the website and return to my online studies, because I could not carry on without certain input. 

•	Challenges I encountered whilst coding this website: 

1)Paint Frames Problem
Idea to put the photos in these frames that look like they are drawn with paint.
My partner made the frame with the right colour on Inkscape and the right shape. 
I cropped the images in circles. 
Did a very complex CSS code to make the frames always stay on top of the pictures for different screen dimensions (for the responsiveness). I had no clue how to do this but found someone who had wanted to do the same on stack overflow and it worked! I even decided to make it so that the frame disappears on small mobile screens, so on a computer when I gradually slid the screen small it looked very cool when the frame was getting smaller and then disappeared. 


However. When I thought that the site is “completed”, and I bought the domain and uploaded it on a server and put it online, the site was having this massive white space on the right side of the website. I could scroll horizontally, and half of the content was my site and half was white space. I figured out that the problem comes from the frames somehow.
The solution:  I just attached the images to the frames on gimp, making it just one image. This significantly simplified my title page code, and this sorted the problem. 

2) Unexpectedly, the site was not being responsive on phones when I published it online.

I had done everything I thought is needed to make my site responsive. After I bought the domain and uploaded my site on infinity free, I had a look at the site on a phone, and to my horror, realized that the mobile version of my site is basically the computer display version made small. You could see everything, but the images and letters were so small, you could not read without zooming in. 
This worried me quite a lot at first, I thought I must have made some fundamental mistake. 

I looked online for solutions to a similar problem and luckily found a fix very quickly- I just had to add the viewport meta tag to my html head and the @viewport rule to my CSS. 

After I made the website (the first version of it), I sent it to many people I know- friends, social groups online, etc and asked for feedback. 

I made a list of what people had said and decided what to act on and change. 
Here are some of the feedback ideas I got: 

1)	Connect the info about classes to the timetable.
-done
2)	Make the map zoomed out so people immediately can tell where the place is. 
-realized that google maps lets you manipulate the map image as a user, so no need to do this.
3)	Make it less scrolly on the About page- the sections were very long, and someone said they find it difficult to scroll a lot to get back. 
-Created “Go to top” button.
4)	Make the photo of the garden plans such that on a phone it can get enlarged so people can read the text and see the details. 
5)	Two people said that they find the three contact forms a bit confusing and would prefer them to be drop down or something less obvious. 
-done
6)	One person said that they find it confusing that the portal page has a nav bar and buttons that take you to the same places. They suggested I get rid of the nav bar and just leave the buttons. 
7)	This person also suggested that the About page has a vertical rather than a horizontal navbar.
8)	Make How to become a volunteer part of the park navbar so it can be found easier. 
-done


Then I had to make the site secure and do a Search Engine Optimization, so the site is easy to find. 

Subdomains
I wanted to make subdomains for beechwood club and hillfields park because the two things are quite separate. I set two subdomains in infinity free and transferred files to them. When I fixed the links in my index.html files, the links from the domain to the subdomains worked, but the links from the subdomains to the main domain did not work. 
Later I found that I need to name the links from my subdomain to the main domain differently, and it worked. 

To make the site “secure” – make it turn into https rather than just http. 
I followed the rules of infinity free and Let’s Encrypt. I chose Let’s encrypt as a provider. Sometimes the tutorials and what people suggested on the Infinity free forum was not matching what you really have to do, so through trial and error I finally got to haw it actually should be done. 
-	I got The SSL (Secure Sockets Layer- Protocol for web browsers and servers that allows for the authentication, encryption and decryption of data sent over the Internet.) certificates from Let’s Encrypt .
-	Then I had to make sure that all my site visitors are forced to go to the https//: version of my site: I did this using .htaccess

To do Search Engine Optimization:

1) Registered the website as a website of the places on google maps
2) Added the website to the facebook pages of the two places. 
3)  I registered with Google Analytics, set up an account and added the websites as properties. 


Other things I did for the site’s SEO: 
1)	On-site SEO

-	Made a Key Word research
-	Made sure the titles of the pages have key words
-	Made sure key words are in the h1, h2, h3 of the HTML files
-	Changed links between my site to include key words, rather than just state “click here” or “about”. 
-	Wrote a clear, informative meta description. 
-	Try to update the content of the site as frequently as possible.

2)	Off-site SEO
-	Contact websites that score high on searches and ask them to add our website to their content. I did this and unfortunately received no response, even though their sites would benefit from having my website included. They were all sites giving information about things to do for kids in Bristol.

Despite doing all the above for the SEO of the site, the site still scores very low in google searches. Only the subdomain for Beechwood Club scores higher. 

I guess that the reason for this is that the website is about a lot of things, so it is probably hard for the google spiders to place it and easily identify its main topic. 

Maybe I will need to separate this website in two websites- one just about the park, and one just about the hall, to get a better SEO. 

Other things I could do for the site’s SEO in the future are to cite our cite more on social media, and on articles written on other websites and media. 


