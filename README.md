# Rock Paper Scissors with Google Teachable Machine

- [Play the game](https://silviueftimiedev.web.app)
- [Video Demo](https://www.youtube.com/watch?v=6poEnjJL0jI)

I have used again the magic of Google to train a visual machine learning model and turn everything into a classic game for my kids: Rock Paper Scissors.

#### Step 01: using Teachable Machine, Preparing training data (classes)
Open your webcam and grab some picture for every class:
- 👊 0 = Rock 
- 🤚 1 = Paper 
- ✌️ 2 = Scissors
- None = a default class

![step01](https://github.com/seftimie/Rock-Paper-Scissors-with-Google-Teachable-Machine/raw/main/screens/1.jpg)

#### Step 02: using Teachable Machine, Training (Don't switch tabs!)
In less than 1 min you will have your model ready for testing.

![step01](https://github.com/seftimie/Rock-Paper-Scissors-with-Google-Teachable-Machine/raw/main/screens/2.jpg)

#### Step 03: Preview and test the Model
Do some testing

![step01](https://github.com/seftimie/Rock-Paper-Scissors-with-Google-Teachable-Machine/raw/main/screens/3.jpg)

#### Step 04: Export the model (using Tensorflow.js option with Upload my model).
Grab the snippet code generated and let's create the game.

![step01](https://github.com/seftimie/Rock-Paper-Scissors-with-Google-Teachable-Machine/raw/main/screens/4.jpg)

#### Step 05: import Vue JS, Tailwind CSS, Tensorflow js + Teachable Machine in html file.
Mix all things together. Add some sounds with Minions (winning/losing part).

![step01](https://github.com/seftimie/Rock-Paper-Scissors-with-Google-Teachable-Machine/raw/main/screens/5.jpg)

#### Step 06: test the game
If everythings Ok... then upload all code on github and host the game on firebase hosting. 
When playing, I recommand using a "white background" or (re)train with better images, export the model and then replace line 145: const URL = "https://teachablemachine.withgoogle.com/models/l02IbpV7q/"; from index.html with your model url.

![step01](https://github.com/seftimie/Rock-Paper-Scissors-with-Google-Teachable-Machine/raw/main/screens/6.jpg)

Enjoy it.


