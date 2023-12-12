## What is Jitsi Meet?
[Jitsi Meet](https://jitsi.org/jitsi-meet/) is a free and open source video conferencing solution. You can deploy it yourself for a free private video conferencing solution to meet, video chat with your friends and colleagues. It offers all the features that the other leading video conferencing solutions have, such as screen sharing, recording, polls, etc. It also has client applications available for desktop & mobile devices.

## Acorn
Acorn is designed to simplify running modern  cloud-native apps on the public cloud. That makes it the ideal candidate for running applications like Jitsi meet. It also provides a big free sandbox that anyone can use to run their applications.

## Running Jitsi Meet on Acorn
Run the Jitsi Meet application on Acorn by deploying the image `ghcr.io/infracloudio/jitsi-meet-acorn:v#.#.#-#`. Optionally you can specify the timezone of the deployment to your own by updating the `TZ` argument. The default timezone is `America/Los_Angeles`.