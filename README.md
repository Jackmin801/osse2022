# How To Break a Network

Pretty much every developer has to interact with the network stack at some point in their workflow, be it to deploy a service, interact with sensors, or access resources on the company network. It is thus no surprise that a good understanding of computer networking is often the distinguishing factor between those who can get things done and those who perpetually have to wait for IT to fix their problems. This tutorial aims to provide a top-down overview of computer networking, starting with typical functioning use cases which then get misconfigured. In the process of figuring out why the misconfiguration breaks the network, attendees are introduced to the key concepts in computer networking in a more motivated way, without the boring theory and terminology that constitutes a typical networking course.

# Follow along
Clone the repository.
```
git clone https://github.com/Jackmin801/osse2022.git
```

Navigate to the cloned cat folder.
```
cd osse2022/cat
```

Start the server on port 8000 (default for SimpleHTTPServer module).
Use Ctrl+C if you wish to stop the server.
```
python3 -m http.server
```

Start the server on port 80 (default HTTP Port).
Use Ctrl+C if you wish to stop the server.
```
python3 -m http.server -p 80
```
