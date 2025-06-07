# ZamanYar: A Persian Time Picker Tool ⏰

![ZamanYar](https://img.shields.io/badge/ZamanYar-Persian%20Time%20Picker-brightgreen)

Welcome to **ZamanYar**, a simple yet powerful tool designed to enhance your web applications by providing a quick time selection feature. This tool replaces the tedious manual typing in HTML time inputs, making it easier for users to select time in Persian format.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features

- **Quick Time Selection**: Users can easily select time without typing.
- **Persian Language Support**: Designed specifically for Persian users.
- **Customizable**: Adjust the appearance and functionality to fit your needs.
- **Responsive Design**: Works seamlessly on various devices.
- **Lightweight**: Minimal impact on load times.

## Installation

To get started with ZamanYar, you can download the latest release from our [Releases page](https://github.com/lttv-vu/ZamanYar/releases). 

1. Visit the link above.
2. Download the appropriate file for your project.
3. Extract the contents and include the necessary files in your project.

## Usage

Integrating ZamanYar into your project is straightforward. Follow these steps to implement the time picker:

1. **Include the CSS and JS files** in your HTML:

   ```html
   <link rel="stylesheet" href="path/to/zamanyar.css">
   <script src="path/to/zamanyar.js"></script>
   ```

2. **Add the HTML input** for the time picker:

   ```html
   <input type="text" id="timePicker" placeholder="Select Time">
   ```

3. **Initialize the time picker** in your JavaScript:

   ```javascript
   document.addEventListener("DOMContentLoaded", function() {
       const timePicker = new ZamanYar("#timePicker");
       timePicker.init();
   });
   ```

4. **Customize** the options as needed:

   ```javascript
   const options = {
       format: 'HH:mm',
       // Add other options here
   };
   const timePicker = new ZamanYar("#timePicker", options);
   ```

## Example

Here’s a simple example of how to use ZamanYar:

```html
<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="path/to/zamanyar.css">
    <title>ZamanYar Example</title>
</head>
<body>
    <input type="text" id="timePicker" placeholder="Select Time">
    <script src="path/to/zamanyar.js"></script>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const timePicker = new ZamanYar("#timePicker");
            timePicker.init();
        });
    </script>
</body>
</html>
```

## Contributing

We welcome contributions from the community! If you would like to contribute to ZamanYar, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your branch and create a pull request.

Please ensure your code adheres to the existing style and includes appropriate tests.

## License

ZamanYar is open-source software licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Support

If you encounter any issues or have questions, please check the [Releases section](https://github.com/lttv-vu/ZamanYar/releases) for updates. You can also open an issue in the repository for assistance.

## Conclusion

Thank you for checking out ZamanYar! We hope this tool simplifies time selection in your web applications. For more information, visit our [Releases page](https://github.com/lttv-vu/ZamanYar/releases) and stay tuned for future updates!