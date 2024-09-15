# AudioPlayerCLI

A simple Java-based command-line audio player that allows users to play, stop, reset, and quit an audio file. This project uses the `javax.sound.sampled` package to handle `.wav` audio files, providing basic playback functionality via an interactive command-line interface.

## Features

- **Play**: Start playing the audio file.
- **Stop**: Pause the audio at its current position.
- **Reset**: Rewind the audio to the beginning.
- **Quit**: Stop the audio and exit the program.

## Technologies Used

- **Java**: Core programming language.
- **javax.sound.sampled**: Used for audio handling and manipulation.

## How to Run

### Prerequisites:
- Java 8 or above must be installed.
- Ensure you have the `.wav` audio file named `jamal_jamaloo.wav` in the project directory.

### Steps:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Shailesh2003-arch/AudioPlayerCLI.git
2. Navigate to the project folder:
   cd AudioPlayerCLI
3. Compile the Java program:
   javac AudioPlayer.java
4. Run the program:
   java AudioPlayer

Commands
When the program is running, you can use the following commands:

P: Play the audio.
S: Stop the audio.
R: Reset the audio to the start.
Q: Quit the program.

Folder Structure

├── AudioPlayerCLI/
│   ├── AudioPlayer.java
│   └── jamal_jamaloo.wav

Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request. Please ensure your changes are well-documented.

License
This project is licensed under the MIT License.


