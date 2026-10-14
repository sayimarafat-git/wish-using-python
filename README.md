# Birthday Wish using Python 🎉

A simple Python project that creates a colorful birthday wish animation in the terminal with optional music.

Created by Ms Saim.

## About

This project is designed to make birthday wishes more fun and personal. It uses terminal art, colorful text, and a music track to create a special surprise for your friend.

The code is intentionally simple so anyone can customize it easily.

## Features

- Colorful birthday art in the terminal
- Multiple art templates in the `arts/` folder
- Custom color codes and text effects
- Optional background audio using the included MP3 file
- Easy setup with a single requirements file

## Project Structure

```text
wish-using-python/
├── arts/
│   ├── default.py
│   ├── plainart.py
│   └── art_2.py
├── HappyBirthday.MP3
├── config.py
├── help.txt
├── main.py
├── README.md
├── requirements.txt
├── LICENSE.md
└── .gitignore
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/sayimarafat-git/wish-using-python.git
cd wish-using-python
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Make sure the MP3 file is available in the project folder:

```text
HappyBirthday.MP3
```

## Configuration

Open `config.py` to customize the animation:

```python
artFile = "default"
speed = 0.0015
codePrint = False
playAudio = True
audio = 'HappyBirthday.MP3'
```

### Change the art style

The project reads the selected file from the `arts/` folder.

Example values:

```python
artFile = "default"
artFile = "plainart"
artFile = "art_2"
```

### Customize colors

The `help.txt` file includes:

- custom artistic characters
- color code shortcuts
- emoji options
- ready-made birthday art patterns

You can use those characters and colors inside the art files to make the output look unique.

## Running the Project

Run the script with:

```bash
python main.py
```

On some systems, you may need:

```bash
python3 main.py
```

## Customization Tips

- Open the `arts/` folder and choose the design you like best.
- Change `artFile` in `config.py` to switch templates.
- Edit `speed` to make the animation faster or slower.
- Use `help.txt` to build your own personalized message.

## Notes

- The repository is built for a fun terminal experience.
- If you want a different birthday message, you can edit the art or text in the art files.
- Keep the volume high for the best effect while the animation runs.

## Disclaimer

Check `help.txt` for sample alphabets, color codes, and birthday art patterns. You can replace names, messages, or symbols to personalize your wishes.

## Credits

Created with love for birthday celebrations.

If you enjoy this project, give it a star on GitHub! 🌟

## License

This project is licensed under the MIT License. See `LICENSE.md` for details.
