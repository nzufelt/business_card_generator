# Business Card Generator app project
_Student handout_

Most apps involve collecting user input and doing something with it. Think about the apps that you use. Don't most of them involve collecting information from users, and then performing some action based on that? In this project, we'll do exactly that, on a small, but still realistic, level. We'll be creating an app that generates business card layouts for its users: they enter some personal data about themselves, and your app turns that into an attractively designed [business card](https://business.tutsplus.com/articles/7-tips-on-what-information-to-put-on-your-business-card--cms-25194).

Here's a [video showing off the structure of the app](https://www.loom.com/share/f168d5d1621740c78fbc5810e2896e24), without any design. You'll want to add far more of your own spin on it, especially since I didn't even make a business card shape on the second screen!

### Step One: Design and User Personas

The two most important questions to ask yourself in designing this app are: _what data should I collect from my users?_, and _how should I present their information back to them as a business card?_ In order to do this well, you should:

* Determine all possible fields that you might want to collect: first name, last name, title, company, phone number, email, etc.
* Create some user personas based on how you expect people to use business cards and their needs, as well as some "troublesome" user personas of people who might try to exploit your app or the users of your app. For example, should you not force users to put their home address?
* Determine at least one design for your business card that is presentable and that you like. The information should be clear and appropriately varying in size — for example, the name should be prominent!

One important consideration is the aspect ratio of your business card. While the aspect ratio of business cards is not standardized, a very common ratio is 1.586: meaning that the card is 1.586 times wider than it is tall.

### Step Two: Form and Function

Create the basic functionality of the form which can move to a new screen. It should be roughly like mine above: a form in which users can enter their information, and that information is (clumsily) displayed on the next screen.

### Step Three: Minimum Viable Product (MVP)

Create a well-designed, fully functional app, complete with well-designed views (especially the business card display) and well-chosen form fields.

### Extensions

The following are some ideas for ways you might extend the app.

* Offer multiple possible business card layouts for people.
* Offer the ability to add social media handles, displayed with the built-in logos. Note that those icons can be downloaded (with TONS of guidelines surrounding their use) from the social media sites' "branding pages". For example, here is [Instagram's branding page](https://en.instagram-brand.com/assets/icons).
* Automatically clean up user inputs. For example, you could choose to capitalize names (but are you sure that you know how all names should be capitalized?). For an extra challenge, you could take any text that's put into the phone number text field and format it to look like a proper number.
* For more practice with data practices, you could create a `User` struct/class which contains properties for each field of your form. Then, your subviews would just take a `user` variable, and not all the fields of the Form.
