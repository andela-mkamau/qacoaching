# NON-FUNCTIONAL TESTING

Non-functional testing encompasses the testing of the non-functional aspects of the application which affect usability, efficiency, reliability and performance. This includes, but is not limited, to test parameters such as security, performance under load, availability in shaky networks, accessibility, portability to different platforms, scalability and so on.

I will be applying various non-functional tests to the application under tests — the Android application [Omni-Notes](https://github.com/andela-mkamau/Omni-Notes).

The following matrix will be used:

## Configuration changes

This will check the impact of configuration changes on the performance on the app. The goal of this tests is to ensure that application state is restored correctly upon any configuration changes.

The tests will involve:

- Changing phone orientation while editing notes
- Using the application in multi-window mode
- Killing the application in the background

## Perfomance and Load Testing

These tests seek to check how the application performs under various loads.

Testcases include:

- Add excessively large text entries
- Add excessively large file attachments
- Add a huge number of notes
- Launch the app in extremely memory contained platform
- Key bashing : random swiping and tapping to produce strange errors
- Launch the app in various difference devices.
