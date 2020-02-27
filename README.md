# React Native Calendar Events Cross

A React Native module to help access and save events to iOS and Android calendars.

Note: This is forked library from original react-native-calendar-events by wmcmahan. Thanks for the library and all the credit goes to him. I just added missing part of iOS attendees editing functionality for custom use picked from 1.6.0 version of this library.

## Documentation

Original documentation can be found from the following URL.
(https://github.com/wmcmahan/react-native-calendar-events)

## Attendees object to modify event attendees

Android - {"url":<email>, "firstName":<attendee name>}
iOS - {"url":<email>, "firstName":<attendee first name>, "lastName":<attendee last name>}
  
details = {
  .....
  .....
  attendees: [
    {"url":<email>, "firstName":<attendee first name>, "lastName":<attendee last name>},
    {"url":<email>, "firstName":<attendee first name>, "lastName":<attendee last name>}
    ....
  ]
}
  
RNCalendarEvents.saveEvent(<Title Of the Event>, details) - Return a promise.



## Authors

* **Will McMahan** - Initial code - [github.com/wmcmahan](https://github.com/wmcmahan)

See also the list of [contributors](https://github.com/wmcmahan/react-native-calendar-events/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/wmcmahan/react-native-calendar-events/blob/master/LICENSE.md) file for details

## Acknowledgments

* Big thanks to all who have contributed, raised an issue or simply find use in this project. Cheers!
