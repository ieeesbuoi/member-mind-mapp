<h1 align="center"> IEEE Member Mind Map </h1>

<em>A web application designed to make it easy to connect with and contact members of various teams and subteams of the IEEE University of Ioannina Student Branch. </em>

## Project Set Up

These instructions will get this project up and running on your local machine.

### Prerequisites

You will need to install Node.js and its package manager, NPM.

##### Arch Linux
``` 
pacman -S nodejs npm
```

##### Ubuntu and Debian based distros (Linux Mint, ElementaryOS, bash on Windows etc.)
```
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs
```
Note: you might also need the build tools:
```
sudo apt-get install -y build-essential
```

##### RHEL, CentOS, Fedora
```
curl --silent --location https://rpm.nodesource.com/setup_6.x | sudo bash -
sudo yum -y install nodejs
```
If you need the build tools:
```
sudo yum install gcc-c++ make
```

##### Gentoo
```
emerge nodejs
```

##### openSUSE and SLE
```
zypper install nodejs4
```

### Installing

First, you need to clone the repository. Run the following command:

```
git clone https://github.com/ieeesbuoi/member-mind-mapp.git
```

Enter the repository:

```
cd member-mind-mapp
```

Install dependencies:

```
npm install
```

## Running Tests

### Note: Tests are currently not available.

Run the following command in your terminal
```
npm run test
```
or just
```
npm test
```
or, if you're really lazy
```
npm t
```

## Deployment

You can run the application live by entering
```
npm start
```
## Built With

* [React](https://reactjs.org/) - Front End Framwork
* [Create React App](https://github.com/facebookincubator/create-react-app) - Dependency Management
* [Semantic UI React](https://react.semantic-ui.com/) - CSS Framework

## Contributing

This project is still in very early stages and we are not accepting contributions until we have a working base product.

## Authors

This project is being developed by the IEEE University of Ioannina student branch


See also the list of [contributors](https://github.com/czonios/member-mind-mapp/graphs/contributors) who participated in this project.

## License

MIT License

Copyright (c) 2017 IEEE UoI Student Branch

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
