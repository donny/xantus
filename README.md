# xantus

Xantus is a simple API.AI agent for Google Home.

### Background

This project is part of [52projects](https://donny.github.io/52projects/) and the new stuff that I learn through this project: [API.AI](https://api.ai).

I've got a [Google Home](https://madeby.google.com/home/) (US version) to play with for a few weeks. It works well in Australia although sometimes it gives me the temperature in Fahrenheit rather than Celcius. We could create a custom Google Home integration using [API.AI](https://api.ai). This project will be code-free and it is a way for me to learn more about API.AI.

### Project

Xantus is ...

### Implementation

Google bought API.AI in September 2016 and it requires you to use this platform to create actions for Google Home. Make sure that the API.AI account is the same as the Google account used by the Google Home device. Otherwise, we won't be able to test our actions on the actual hardware.

Login to API.AI and create a new agent as shown below:

![Screenshot1](https://raw.githubusercontent.com/donny/xantus/master/screenshot1.png)

We add some sample data, in this case Easter Egg data, that allows us to test some predefined intents:

![Screenshot2](https://raw.githubusercontent.com/donny/xantus/master/screenshot2.png)

An intent is a way to define phrases that trigger an action and responses following the phrases. As an example, take a look at the `easteregg.why_chicken_cross_road` intent below:

![Screenshot3](https://raw.githubusercontent.com/donny/xantus/master/screenshot3.png)

The red arrow specifies the phrases that can trigger the `easteregg.why_chicken_cross_road` intent. For example: `do you know why chicken crosses the road`. The blue arrow specifies the corresponding responses. For example: `to complete another level of Angry Birds`.

After defining some simple intents, we could deploy it by going to the `Integrations` section of the side menu. And turn on the `Actions on Google` integration as shown by the two screenshots below:

![Screenshot4](https://raw.githubusercontent.com/donny/xantus/master/screenshot4.png)

![Screenshot5](https://raw.githubusercontent.com/donny/xantus/master/screenshot5.png)

According to Wikipedia, [Actions on Google](https://en.wikipedia.org/wiki/Actions_on_Google) is a program for developers of "Actions" (software applications) that run via Google Assistant on devices such as the Google Home smart speaker and the Google Pixel smartphone and on the Google Allo mobile app.

After setting up Actions on Google, we could test our agent using the web simulator as shown by the two screenshots below:

![Screenshot6](https://raw.githubusercontent.com/donny/xantus/master/screenshot6.png)

![Screenshot7](https://raw.githubusercontent.com/donny/xantus/master/screenshot7.png)

### Conclusion

...
