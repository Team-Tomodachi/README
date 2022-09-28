# README
Read more about the Tomokuru platform

<img width="170" alt="Screen Shot 2022-09-28 at 19 36 33" src="https://user-images.githubusercontent.com/92012639/192758256-c020dae7-c5b3-42fe-a925-63717632fc96.png">


Welcome to Tomokuru. Tomokuru is an online platform that integrates a user-oriented mobile app and a vendor-orientated web site. The purpose of Tomokuru is to give individual users a new way to meet people with similar hobbies and interests, browse events that are going on in the city, and search for different types of venues where they may host or attend social gatherings. Vendors also have a new way to manage multiple venues to offer various packages that appear on the users venue screen.

Inside the Tomokuru organization, you will find 3 main respositories. The TomoKuru-Mobile app was built with React native and deployed through Expo Go. The Tomokuru-Web app was built with React and deployed on Google cloud services. The TomoKuru-Backend was developed with PostgreSQL and we utiziled Firebase for authentication and image handling. 

# How to download / access application

iOS - exp://u.expo.dev/update/414cc358-383e-474d-9ea1-091431f49bf8

<img width="309" alt="Screen Shot 2022-09-28 at 19 33 47" src="https://user-images.githubusercontent.com/92012639/192757689-a8c4d8c9-9e13-4b23-83e3-5049d90608e0.png">

android - exp://u.expo.dev/update/f8bbc29b-53f8-41ee-a1bd-4913330886ce

<img width="307" alt="Screen Shot 2022-09-28 at 19 33 17" src="https://user-images.githubusercontent.com/92012639/192757590-107593fe-2189-4965-8c10-16b07a8fd46d.png">


WEB - http://tomokuru-web.i-re.io/


# Presentations / Media
    - youtube tba
    - slideshow
    
    
# Have any feedback?
We'd love to hear your questions, comments, or concerns! 

please mail stevemckillop@gmail.com 


# Meet the Team / Roles (github / linkedIn / email) 

Tech Lead / Design - Adam 

Product Owner/Front-end - Steve

Frontend Lead (mobile) - Han

Fullstack (web app) - Ken 

Backend Lead / Frontend(web app) - Jason


# Styling Page

**Figma**

[https://www.figma.com/file/SjL7CVRzYaueUC5BV76cxW/Untitled?node-id=0%3A1](https://www.figma.com/file/SjL7CVRzYaueUC5BV76cxW/Untitled?node-id=0%3A1)

**Fonts** 

[https://fonts.google.com/specimen/Kanit](https://fonts.google.com/specimen/Kanit)

[https://fonts.google.com/specimen/Open+Sans](https://fonts.google.com/specimen/Open+Sans)

Kanit Black 900 for “Tomo” Black 900 Italic for “Kuru” (use spans) **ONLY FOR LOGO**

Kanit ExtraBold 800 & Italic for **#h1**

Kanit Bold 700 & Italic for **#h2~h3**

Card Titles = Open Sans - Bold,(@20px)

Open Sans Regular 400 and Italic for **body**

Open Sans Light 300, Medium 500, SemiBold 600, and Bold 700 (also Italic variants) are also OK to differentiate **sections** where needed. Try not to go beyond that. The really bold and punchy page divisions should be in Kanit.

**Colors**

Accent orange-yellow (buttons mostly)

#FCB90F main accent color for buttons, etc.

#CC960C darker alternate, for clicked/touched buttons etc. as needed (pref over lighter)

#FFD15C lighter alternate, for clicked/touched buttons etc. as needed

Body Text

#000000 black

Background and section boxing

#FFFFFF white

#DFDFDF  off-white

#B5B5B5 light gray

**Notes**

Buttons should be large, more wide than tall, and have higher padding on left/right

5px (~0.25rem) rounding on boxes

black text

no drop shadows (a pain to work with and keep uniform)

no strokes or borders

try to use blocks of color, ~~rather than lines~~ to divide sections (lines are probably ok)

~as an exception I think the safety screen buttons should still be green, the two negative ones should be shades of red.

#1DAE23  Safe

#D92222 Not good

#7C0404 POLICE

In general, all text should be black, all buttons and interactive elements should use the accent color, all boxes should be variants of white and gray

I’m going to need to test some on mobile/web, Kanit is mainly a display font-especially in bold. So it might not look great on buttons. In which case, Open Sans may be best there

 

# ~~~ below this line is old ~~~

## fonts

Open Sans for body, sections, etc.

[https://fonts.google.com/specimen/Open+Sans](https://fonts.google.com/specimen/Open+Sans)

Salsa for logo and ..?

[https://fonts.google.com/specimen/Salsa](https://fonts.google.com/specimen/Salsa)

~~Courgette for logo and..?~~

[https://fonts.google.com/specimen/Courgette](https://fonts.google.com/specimen/Courgette)

## NEW COLORS

![Screenshot 2022-09-15 202840.png](Styling%20Page%203a5be9de298a4cc096966854bd639d1a/Screenshot_2022-09-15_202840.png)

## ~~COLORS~~

 [https://coolors.co/ded702-fcf53b-fef985-ffffff-000000-b6b6b6-e0e0e0](https://coolors.co/ded702-fcf53b-fef985-ffffff-000000-b6b6b6-e0e0e0)

![tomokuru_colors2.png](Styling%20Page%203a5be9de298a4cc096966854bd639d1a/tomokuru_colors2.png)

citrine  for visited links, hover?, etc

lemon-yellow for accents (main color)

canary for hover? secondary to lemon-yellow?

**DO NOT PUT WHITE TEXT ON YELLOW BACKGROUND**

**OR YELLOW TEXT ON WHITE BACKGROUND**

white background

black some sections?

gray-x-11-gray for sections, form box outlines, etc.

gainsboro as a lighter option



# Libraries

## Axios

- Handling network request

## React Query

- Handling caching and updating for server data

## React Navigation

- Handling screens navigation

## ****React Native Zephyr****

- Styling with Tailwind syntax

## Expo Vector Icons

- Contains multiple icons set

## Zustand

- Manage local state

## Formik

- Handle form

## React Native Paper

- Pre-built components with Material UI design

## ****FastImage****

- Caching and displaying Image






# Libraries

## Axios

- Handling network request

## React Query

- Handling caching and updating for server data

## React Navigation

- Handling screens navigation

## ****React Native Zephyr****

- Styling with Tailwind syntax

## Expo Vector Icons

- Contains multiple icons set

## Zustand

- Manage local state

## Formik

- Handle form

## React Native Paper

- Pre-built components with Material UI design

## ****FastImage****

- Caching and displaying Image


#ENDPOINTS
his page will be a list of endpoints to be used by the front end

the root for all APIs will be `/api/` for example to make a get call to the test endpoint would be `/api/test`

If you are running the backend server - the SWAGGER UI is on the `api_dev_docs`

## **END POINTS TODO LIST:**

- `groups/` - //returning all tags in an array for each groups as well - DONE
    - 
    
    group: {
    name: “sth”
    tags: [“tag 1” ,”tag 2”]
    }. ⇒ `/singlegroup/:group_id`
    
- ~~Create an event api - check venue_id if null insert NULL venue~~
- `events/` - //joins for group name, venue - remove null venues -DONE
- `events/messages/:event_id` -//user name (Join), message content, date, photo url - DONE
- List of smoking (give to Han to filter):
    - No Smoking
    - Smoking Outside Only
    - Electronic Cigarettes Only
    - Smoking and Non-smoking areas
- Finish venue seed files - and smoking, seating capacity (integer), outdoor seating, extra information
- Seating Capacity Filter for venues ≤ 100 & Tags filter (By Hanh)
- 2 NEW Endpoint return all groups (1) and all events (1) where the user is a member -DONE

## Active Endpoints

GET `/test` - This end point is for testing purposes only

GET `users/:email` - get a single user information by email address

```
router.get("/:email", async (req, res) => {
  const { email } = req.params;
  try {
    const user = await db("users")
      .where("email", email)
      .select(
        "id",
        "email",
        "first_name",
        "account_type",
        "account_active",
        "city_ward",
        "prefecture",
        "title"
      )
      .timeout(1500);
    res.send(user).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

GET `users` - get all users

```
router.get("/", async (req, res) => {
  try {
    const users = await db("users").select("*").timeout(1500);
    res.send(users).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

POST `users` - create account

```jsx
router.post("/", async (req, res) => {
  const {
    email,
    first_name,
    firebase_id,
    account_type,
    city_ward,
    prefecture,
    title,
  } = req.body;
  const newUser = {
    account_active: "active",
    email: email,
    first_name: first_name,
    firebase_id: firebase_id,
    account_type: account_type,
    city_ward: city_ward || "",
    prefecture: prefecture || "",
    title: title || "",
  };
  try {
    await db("users").insert(newUser);
    res.status(200).end();
  } catch (err) {
    res.send(err).status(500);
  }
});
```

PATCH `users/:email` - update user account

```jsx
router.patch("/:email", async (req, res) => {
  const { email } = req.params;
  const edits = req.body;
  try {
    await db("users").where("email", email).update(edits);
    res.status(200).end();
  } catch (err) {
    res.send(err).status(404);
  }
});
```

PATCH `user/:email/activation` - inactivate account

```jsx
router.patch("/:email/activation", async (req, res) => {
  const { email } = req.params;
  try {
    await db("users")
      .where("email", email)
      .update({ account_active: "inactive" });
    res.status(200).end();
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- GET `/venues` - get all venues

```jsx
router.get("/", async (req, res) => {
  try {
    const venues = await db("venues").select("*").timeout(1500);
    res.send(venues).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- POST `/venues` - create venue

```jsx
router.post("/", async (req, res) => {
  const {
    user_id,
    location_name,
    city_ward,
    prefecture,
    phone_num,
    address,
    venue_email,
    description,
    num_seats,
    smoking,
    outdoor_seating,
    venue_url,
    photo_link,
  } = req.body;
  const newVenue = {
    user_id: user_id,
    location_name: location_name,
    city_ward: city_ward,
    prefecture: prefecture,
    phone_num: phone_num || "",
    address: address || "",
    venue_email: venue_email || "",
    description: description || "",
    num_seats: num_seats || 0,
    smoking: smoking || "",
    outdoor_seating: outdoor_seating || false,
    venue_url: venue_url || "",
    photo_link: photo_link || "",
  };
  try {
    await db("venues").insert(newVenue);
    res.status(200).end();
  } catch (err) {
    res.send(err).status(500);
  }
});
```

- GET `venues/:id` - get all by owner/creaters USER_ID

```jsx
router.get("/:id", async (req, res) => {
  const { id } = req.params;
  try {
    const venues = await db("venues")
      .where("user_id", id)
      .select("*")
      .timeout(1500);
    res.send(venues).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- GET `venues/city/:city` venue - multiple venues by city

```jsx
router.get("/city/:city", async (req, res) => {
  const { city } = req.params;
  try {
    const venues = await db("venues")
      .where("city_ward", city)
      .select("*")
      .timeout(1500);
    res.send(venues).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- GET `venues/prefecture/:prefecture` - multiple venues by Prefecture

```jsx
router.get("/prefecture/:prefecture", async (req, res) => {
  const { prefecture } = req.params;
  try {
    const venues = await db("venues")
      .where("prefecture", prefecture)
      .select("*")
      .timeout(1500);
    res.send(venues).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- PATCH `venues/:id` - update venues by venue ID

```jsx
router.patch("/:id", async (req, res) => {
  const { id } = req.params;
  const edits = req.body;
  try {
    await db("venues").where("id", id).update(edits);
    res.status(200).end();
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- DELETE `venues/:id`  - delete venues by id

```jsx
router.delete("/:id", async (req, res) => {
  const { id } = req.params;
  try {
    await db("venues").where("id", id).delete();
    res.status(200).end();
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- GET `/groups` - Get all groups

```
router.get("/", async (req, res) => {
  try {
    const groups = await db("groups").select("*").timeout(1500);
    res.send(groups).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- GET `/groups/:id` - Get all groups by user_id of creator

```
router.get("/:user_id", async (req, res) => {
  const { user_id } = req.params;
  try {
    const groups = await db("groups")
      .where("user_id", user_id)
      .select("id", "user_id", "group_name", "group_description", "private");
    res.send(groups).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- POST `/groups` - Create a new group

```jsx
router.post("/", async (req, res) => {
  const { group_name, group_description, group_leader, private } = req.body;
  const newGroup = {
    group_name: group_name,
    group_description: group_description,
    user_id: group_leader,
    private: private,
  };
  try {
    await db("groups").insert(newGroup);
    res.status(200).end();
  } catch (err) {
    res.send(err).status(500);
  }
})
```

- POST `/groups/joingroup` - user becomes a member of a group (required in body group_id or user_id)

```jsx
router.post("/joingroup", async (req, res) => {
  const { group_id, user_id } = req.body;
  const newMember = {
    group_id: group_id,
    user_id: user_id,
  };
  try {
    await db("group_members").insert(newMember);
    res.status(200).end();
  } catch (err) {
    res.send(err).status(404);
  }
});
```

- GET `groups/members/:group_id` - get the members of who belongs in the groups

```jsx
router.get("/members/:group_id", async (req, res) => {
  const { group_id } = req.params;
  try {
    const members = await db("group_members")
      .where("group_id", group_id)
      .select("*");
    res.send(members).status(200);
  } catch (err) {
    res.send(err).status(404);
  }
});
```

`/groups/`

router.get("/usermembership/:user_id", async (req, res) => {

const { user_id } = req.params;

try {

const groupList = *await* db("group_members")

.where("user_id", user_id)

.join("groups", "group_members.group_id", "=", "groups.id")

.select("groups.group_name", "groups.id");

res.send(groupList).status(200);

} catch (err) {

res.send(err).status(400);

}

});

`/events/`

router.get("/userattending/:user_id", async (req, res) => {

const { user_id } = req.params;

try {

const eventList = *await* db("event_attendees")

.where("user_id", user_id)

.join("events", "event_attendees.event_id", "=", "events.id")

.select("events.name", "events.id");

res.send(eventList).status(200);

} catch (err) {

res.send(err).status(400);

}

});

## Endpoints in development

- 

## Endpoints needing to be build

- venue - get a single venue
- group - update
- group - delete
- group - get all by user id (member or owner)
