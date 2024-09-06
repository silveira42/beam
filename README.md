# Beam

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/silveira42/beam/blob/main/README.md)
[![pt-br](https://img.shields.io/badge/lang-pt--br-green.svg)](https://github.com/silveira42/beam/blob/main/LEIAME.md)

Beam is a super simple web application that allows you to upload files to a specific folder in you host device and share them with clients via a HTTP server. You can expose this server via a personal VPN or publish it. Keep in mind, this is a very simplistic solution with **no security measures** included, so host at your own risk.

## See it live
[A Beam is hosted here](https://beam.thesilver.com.br)

## Usage
1. Create a folder called Beam in your linux home folder.
2. Add the files you want to share in that directory.
3. Clone the repository at the directory of your choice.
4. Run `docker compose up -d` at the project root.
5. Open `http://localhost:25113` in your web browser.
6. Enter the desired file name in the input field.
7. Click the "Baixar" button to download the file.
8. You can host this to outside your network at your own risk.

## Project Structure
```
.
├── index.html
├── README.md
├── LEIAME.md
├── docker-compose.yml
├── nginx.conf
└── LICENSE
```

## Dependencies
This project does not have any external dependencies. It is built using plain HTML, CSS, and JavaScript.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the GNU GPLv3 License. See the `LICENSE` file for details.

## Acknowledgements
- [JustBeamIt](https://justbeamit.com) for providing a quick file upload service.

## Contact
For more information, visit [The SilverHub](https://thesilver.com.br).
