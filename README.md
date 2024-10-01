# Focus Feen

A project made for [HacktheHill 2](https://devpost.com/software/focus-feen), a three day hackthon. The goal of this project is to help you master concentration by tracking your focused time and providing a score when distractions break your flow. It's designed to help users strengthen their focus skills in a fun and measurable way, turning you into a productivity superhero.

## What it does

Focus Feen uses a camera-based neural network model to analyze head movements and determine whether the user is focused or distracted. It tracks focused time and provides real-time feedback when distractions are detected. Over time, users can improve their focus by engaging in uninterrupted work sessions.

## How we built it

- **Neural Network**: We used [Google's Teachable Machine](https://teachablemachine.withgoogle.com/) to train a model for head pose detection to predict focus or distraction.
- **Frontend**: Developed with React, the user interface interacts with the model’s predictions to update a timer that tracks focused time. The interface was styled with tailwind CSS for a clean and intuitive user experience.

## Try it out

Clone the repository:

### `git clone https://github.com/ymoumine/Focus-Feen.git`

Go to project directory:

### `cd Focus-Feen`

In the project directory, you can run:

### `npm start`


Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## Contributors

- [Yassine Moumine](https://github.com/ymoumine)
- [Kyle Yu](https://github.com/kyle-yu33)
- [Mustafa Sarikaya](https://github.com/MustafaSarikaya)
- [Alexandre M.](https://github.com/Syth-000)

## Acknowledgments

- [Teachable Machine](https://teachablemachine.withgoogle.com/) for making neural network training accessible.
- The [HacktheHill](https://2024.hackthehill.com/) hackathon organizers for inspiring us to create Focus Feen.
  
