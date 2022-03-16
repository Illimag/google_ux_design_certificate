0:00
Hello again. Now that you have some experience with digital wireframing in Figma, and lo-fi paper prototyping, you're ready to start experimenting with some lo-fi digital prototyping. In this video, we'll review the differences between wireframing and prototyping. Then I'll demonstrate how to create a digital prototype in Figma based on wireframes. Remember, wireframes are used to establish an overall structure of the design. In both paper and digital wireframes, you draw each screen a user might experience on a device, like a homepage or user profile page. With prototypes, however, the focus is on understanding how users interact with the design. In other words, the user needs to know what happens when they press a button or tap a menu.
Play video starting at ::51 and follow transcript0:51
Let's pull up the wireframes for the dog walking app that I created earlier. Last time I demonstrated something in Figma, I created a wireframe for the homepage. While you were working on your own project, I went ahead and created the rest of the digital wireframes for the screens I drew on paper. Now we have the homepage from earlier, the schedule page with a date and time, the list of available dog walkers, the dog walker profile page, and the booking confirmation page. You probably noticed that the dog walkers search results page is a lot longer than the others. This is intentional. In a wireframe, the long length signals that the screen will scroll, since we'll be using these wireframes for our prototypes, having the longer screen will allow users to scroll down the screen. Figma has the capability for scrolling long screens built-in. We'll get to this in more detail later.
Play video starting at :1:51 and follow transcript1:51
To make these wireframes into a low-fidelity prototype, we need to show how the user navigates the app from one screen to the next. In a paper prototype, I moved the phone outline to show how the user would navigate from screen to screen. You might also draw lines to show this movement or cut out the screens and stack them. But in a digital low-fidelity prototype, your designs are interactive and mimic the real life navigation between screens. For example, on the homepage, what happens when a user taps the schedule button or clicks the image carousel? Each scenario needs to be accounted for. In a digital low-fidelity prototype, users should be able to click a button and be taken to the correct screen. Let's do that now. The first thing we need to do is label these wireframes. It'll make it a lot easier for us to refer to each screen by number and name. Plus, it clarifies the page's intentions. I've already labeled these wireframes, but here's how you would do it. I'll click on the frame and go to the Layers panel and change the name. Number 1 is the homepage, and I'll do the same with the rest of the screens. Number 2 is schedule page.
Play video starting at :3:10 and follow transcript3:10
Number 3 is the list of available dog walkers.
Play video starting at :3:18 and follow transcript3:18
Then we have number 4, dog walker profile page. Finally number 5, booking confirmation page.
Play video starting at :3:33 and follow transcript3:33
Great. Now we're ready to prototype. The first thing we need to do is change from the Design tab to the Prototype tab. This changes the options for what we can do with each of our wireframe's screens. Now, when I hover over or select the element in the wireframes, notice how a little circle with a plus sign appears on the right side of the element? This is a connection node and it indicates where a prototype connection can begin. For example, what do I want to happen when the schedule button is tapped? I want users to go from the homepage to the scheduling page. I'll click on the connection node and drag the arrow, and a connection arrow appears. We can drag this arrow from the schedule button on the homepage to the scheduling wireframe, which is our desired destination here. When we release the click, there's a connection between the two elements. Now, on the scheduling page, users can pretend to enter the date and time they need a dog walker. When they're done, they'll click the Submit button. I'll connect Submit to the next screen. I'll click on the node and drag the connection arrow from the Submit button to the next wireframe, which is the list of available dog walkers.
Play video starting at :4:55 and follow transcript4:55
Let's assume that the user is interested in this first dog walker. They click Learn more. This button takes them to the dog walker's profile page. I'll connect those two.
Play video starting at :5:11 and follow transcript5:11
Perfect. Now the user has read up on the dog walker and is ready to book. When they click Book, they're taken to this final confirmation page. I'll add this connection arrow too.
Play video starting at :5:24 and follow transcript5:24
Yay! I've created a usable prototype. Let's see it in action. To do this, let's go into presentation view by clicking the Play button in the upper-right corner of the toolbar. Here is my prototype. Now, I'll follow all the steps I just outlined to make sure the prototype works. First, I'll click this Schedule button on the homepage. Then I'll schedule a day and time and click Submit. Here's the list of available dog walkers. Notice how it scrolls to show users all the dog walkers. Pretty cool, right? Next in the user journey, I'll choose to learn more about a dog walker. I'm taken to the dog walker profile page. Finally, I'll book the service. Here I'm on the confirmation page. It seems like I created a usable transaction. It may seem like we're done with the prototype, but there's still more to test. I'll play the prototype again and choose a different dog walker from the list of results. What happens when I click Learn more under dog walker number 3? Nothing, so I need to fix that. I'm going to connect all of these Learn more buttons to a profile page for Jane Doe since that's the only profile I'll use for this low-fidelity prototype. This way, no matter which Learn more button a user selects, they're taken to this example profile page. You could make several profiles for your prototype if you'd like, but I'm keeping it simpler here to save time.
Play video starting at :6:54 and follow transcript6:54
What are we missing on the profile page? I've already connected the Book button to the confirmation page. These other squares are placeholders for images, so I won't worry about those yet. Look at the bar at the top of the screen. See this left-facing arrow? What should happen with this? When users click it, they should go back to the previous page. I'll connect the back button with the previous screen: the list of available dog walkers. Perfect. Now I'll do the same with the rest of the back buttons. They should each be connected to the previous screen.
Play video starting at :7:33 and follow transcript7:33
One more thing -- let's revisit the schedule page. Here on the screen, there's another place a user might click: the Cancel button. The Cancel button should take the user back to the homepage, so I'll make that connection. Now that we're on the homepage, there are more places the user might click. What happens when a user clicks on the Profile icon in the bar at the top of the app. Well, nothing yet, but it should take users to a user profile page, and we're in luck because it just so happens that I've already created that wireframe. Let's check it out. When I want to view a different part of the file, I just hold down the space bar and click on the page to pan around. Great. Here's the wireframe I've drawn up for this profile page. Eventually, on this page, the user can edit their personal details. I'll connect the profile icon to the profile page. Now, I'll connect this page to the homepage using the back arrow up at the top.
Play video starting at :8:39 and follow transcript8:39
I'm back on the homepage. Next, what should happen when the user clicks this headline in the image carousel? It should take them to a list of dog training tips. But right now nothing happens because we haven't created this screen or connected it. This is an entirely different journey for the user. Instead of booking a dog walker, they're reading content, so I need to account for that by providing a screen for the articles. Let me show you how quickly I can create a new screen in Figma.
Play video starting at :9:51 and follow transcript9:51
There we go. I have a totally new page to account for this user journey. Remember, now I need to add a connection arrow to the carousel on the homepage.
Play video starting at :10:14 and follow transcript10:14
Great. Now when the user or usability study participant interacts with the homepage, they've more than one option for where to go. I'll play our prototype one more time and see how I've improved it. Here I am on the homepage again. I've already tested the schedule button, so I'll check our new connections. I'll click the headline here. I'm on the article page. Nice. Now go back. I'll check the profile icon. It works. Next, I'll go through our main transaction again and schedule a dog walker. Let's say I need to cancel. Great, that's working. One more time. On this dog walker search results page, remember how I tried to click the Learn more button on a profile other than the first one and that link didn't work? I'll give that another try. This time, I'll scroll to the bottom and learn more about this person. Nice. It went to our example of a dog walker's profile. I'll book a dog walker and complete the user journey. I did it. There you have it! That's how to build a lo-fi prototype in Figma. But there are lots of moving parts to a prototype. We haven't added images or text or color into the equation. There's a lot left to do to upgrade this low-fidelity prototype to a high-fidelity prototype and ultimately create a usable app. Coming up, you'll learn more about the differences between lo-fi and hi-fi prototyping. You'll even have the chance to show what you've learned by building your own prototype. Keep up the great work.