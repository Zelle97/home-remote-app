# home-remote-app
Simple Home Control Dashboard to start and Shutdown Computers

## Usage

This Project was developed and used to start and shut down a local server.
For this purpose we developed a simple node backend (https://github.com/Zelle97/remote-server) to start and shutdown servers.

For a simpler usage we connected that backend with a frontend dashboard (https://github.com/Zelle97/remote-dashboard) that can be accessed with a browser.

Its quite small and simple but works as intended.

### Config

The remote-server uses a config file. More info [here](https://github.com/Zelle97/remote-server).
The config directory has to be mounted as a volume for the remote-server app to work.

## Docker on Raspberry

Because the automated builds between Github and Dockerhub dont work with different architectures it is recommended to build the Images from source.
You will find the Instructions in the repos of the backend and dashboard.
You can use the image inside of Dockerhub but it will probably be outdated. Just check the last updated and compare it with the source code history to be on the safe side.

##### Author & Licence

If you have any questions or improvement Ideas feel free to open an Issue or a feature request.

**Projects** © [Zelle97](https://github.com/Zelle97), All Projects are released under the MIT License.

> Authored and maintained by Zelle97 · GitHub [@Zelle97](https://github.com/Zelle97)
