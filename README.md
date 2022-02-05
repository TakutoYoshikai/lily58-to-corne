# lily58-to-corne

<img src="./keyboard.jpg" width="500">

This is a keymap that can change Lily58 Pro to like Corne Cherry.

### Usage
**1. setup qmk_firmware**

refer [qmk_firmware](https://github.com/qmk/qmk_firmware/)

**2. clone this repository to qmk_firmware/keyboards/lily58/keymaps/corne**
```bash
cd qmk_firmware/keyboards/lily58/keymaps
git clone https://github.com/TakutoYoshikai/lily58-to-corne.git corne
```

**3. flush firmware**
```bash
make lily58:corne:avrdude
```

### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

### License
MIT License
