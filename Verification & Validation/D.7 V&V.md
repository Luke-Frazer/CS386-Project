# D.7 Verification and Validation #

## Description ##

MyGroceryHelper is a free, simple, and organized way to help you manage shopping and budget with no headaches. The software includes an intuitive menu system that is very easy to operate. The main functions are a calendar that you can manually enter events in and over time the app will learn your shopping habits and schedule them for you. The next main feature is the portfolio. This is a list of everything that you buy and how frequently. This tab also contains information on the best place to shop for the best deals on these items.

*GitHub Link:*

## Verification (tests) ##

### Unit Test ###

#### Test Framework ####

JUnit 5 was used for the Unit tests of this app.

#### Link to Automated Tests ####

#### Example Test Case ####

#### A Print Screen ####

### Acceptance Test ###

#### Test Framework Used ####

JUnit 5 was used for the Unit tests of this app.

#### Link to Automated Tests ####

https://github.com/Luke-Frazer/CS386-Project/blob/main/Verification%20%26%20Validation/ExampleInstrumentedTest.java

#### Example Acceptance Test ####

@RunWith(AndroidJUnit4.class)
public class ExampleInstrumentedTest {
    @Test
    public void useAppContext() {
        // Context of the app under test.
        Context appContext = InstrumentationRegistry.getInstrumentation().getTargetContext();
        assertEquals("com.example.calendarapp", appContext.getPackageName());
    }
}

The code above launches the calendar and verifies that it is running.

#### A Print Screen ####

![image](https://user-images.githubusercontent.com/71099197/165417331-f2aaa3dd-933c-4e31-b358-373e84da1825.png)

## Validation (User Eval) ##

### Script ###

### Results ###

### Reflections ###
