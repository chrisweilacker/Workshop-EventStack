# Workshop-EventStack
Fullstack workshop that incorporates the EventBrite API.

## Step 1
Connect index.html to React and load up an initial page that has a list of Events from the following sample data with an h1 header saying "Events":
[
        { name: 'AngularConnect' },
        { name: 'DevFest' },
        { name: 'JSConf' },
        { name: 'VueConf' },
        { name: 'ReactConf' },
]



## Step 2
Now instead of just listing the events. Have a Text Box and a Search Button in a form that will filter the event list and display the list but filtered based on the exact word in the text box.

## Step 3
Now add another form that will add an Event to your list.

## Step 4
Add in Mongoose to use a db for the Events each event should have the following info:
{
  ID: Number,
  title: String,
  description: String,
  summary: String,
  startDate: String,
  endDate: String,
  cost: Number
}
Create a simple Node server that will run your app and connect to MongoDB.


## Step 5

Add a /events POST and GET Request url that will retrieve all events from the db and store an array of events to the db.

Some sample data which you can use to test on:

[
  {
    ID: 1,
    title: 'ReactConf',
    description: 'The offical Facebook React conference',
    summary: 'Two full days of knowledge sharing and community with people who build and LOVE React.',
    startDate: 'October 24, 2019',
    endDate: 'October 25, 2019',
    cost:420
  },
  {
    ID: 2,
    title: 'DevFest DFW',
    description: 'DevFests are community-led developer events hosted by Google Developer Groups around the globe. GDGs are focused on community building and learning about Google’s technologies. ',
    summary: 'DevFest DFW brings together world-class experts in Android, Web, Cloud, ML/AI, and other technologies to Dallas for 1 day of sessions & workshops.',
    startDate: 'October 19, 2019',
    endDate: 'October 19, 2019',
    cost:30
  },
  {
    ID: 3,
    title: 'JSConf',
    description: 'JSConf US is the only conference where you can learn how to push your favorite language beyond the confines of the browser and into robots, and video games.',
    summary: 'JSConf US has pushed the language outside of its comfort zone, the web browser, and into the forefront of servers, drones, robots and video games. Enjoy a very special day of exciting activities that are sure to make anyone happy from golfing to robot hacking to segway tours during our "choose-your-own-adventure" activity day only at JSConf US.',
    startDate: 'August 12, 2019',
    endDate: 'August 14, 2019',
    cost:850
  },
  {
    ID: 4,
    title: 'VueConf',
    description: 'The offical Facebook React conference',
    summary: 'Two full days of knowledge sharing and community with people who build and LOVE React.',
    startDate: 'March 2, 2020',
    endDate: 'March 4, 2020',
    cost: 795
  },
  {
    ID: 5,
    title: 'NG-Conf',
    description: "The World's best Angular Conference",
    summary: 'The conference for everything Angular',
    startDate: 'May 1st, 2019',
    endDate: 'May 3rd, 2019',
    cost:1100
  },
];

## Step 6
You should now update the frontend to get your list from your server and read the db to get the events not from sample data but the db and schema you created, you should also now be able to add an event to the db with an updated add form.


### A possible olution for each Step can be found in different branches at:
https://github.com/ckallemeyn/Workshop-EventStack
