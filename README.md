# GitHub Contributions Snake

This repository contains a GitHub Action that generates a snake animation based on your GitHub contributions. The snake animation is automatically updated daily and can be displayed on your GitHub profile.

## Features

- 🐍 Generates a snake animation from your GitHub contributions
- 🌙 Supports both light and dark themes
- 🎨 Customizable colors and styles
- ⚡ Automatically updates daily
- 📊 Displays your contribution activity in a fun way

## How It Works

The workflow (`snake.yml`) runs daily at midnight UTC and:
1. Generates SVG and GIF animations of your GitHub contributions
2. Deploys them to the `output` branch
3. Updates automatically with your latest contributions

## Usage

1. Fork this repository
2. Enable GitHub Actions in your forked repository
3. The snake animation will be generated automatically
4. You can find the generated files in the `output` branch

## Customization

You can customize the snake animation by modifying the `snake.yml` file:
- Change colors using the `color_snake` and `color_dots` parameters
- Adjust the output file names and formats
- Modify the schedule for updates

## License

MIT License - feel free to use this for your own GitHub profile! 