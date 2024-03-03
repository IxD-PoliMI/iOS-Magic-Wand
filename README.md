# iOS-Magic-Wand
Author: [Emanuele Della Valle](http://emanueledellavalle.org/) and [ChatGPT 4.0](https://chat.openai.com/share/9d58c3f0-28d9-4224-8433-c199ef52e9fe)

This repo demonstrates how to make a minimal Magic Wand. 
It is a Web-based application for iOS that uses a [WASM](https://webassembly.org/) package generated with Edge Impulse and a fork of the [iOS Motion repo](https://github.com/IxD-PoliMI/iOS-motion).

The WASM package includes a [Feedforward Neural Network for motion detection trained on Edge Impulse](https://studio.edgeimpulse.com/public/358263/latest). It detects three movements of the mobile phone:
- idle: if you keep it in your hand facing up without moving it much
- S: if you draw an S in the air, keeping it facing up
- O: if you draw an O in the air anticlockwise

For more information, check out
- [https://docs.edgeimpulse.com/docs/pre-built-datasets/continuous-gestures](https://docs.edgeimpulse.com/docs/pre-built-datasets/continuous-gestures)

# Bacchetta magica per iOS
Autore: [Emanuele Della Valle](http://emanueledellavalle.org/) e [ChatGPT 4.0](https://chat.openai.com/share/9d58c3f0-28d9-4224-8433-c199ef52e9fe)

Questo repo mostra come realizzare una bacchetta magica minimale. 
È un'applicazione Web per iOS che utilizza un pacchetto [WASM](https://webassembly.org/) generato con Edge Impulse e un fork di [iOS Motion repo](https://github.com/IxD-PoliMI/iOS-motion).

Il pacchetto WASM include una [Feedforward Neural Network per riconoscere movimenti appresa con Edge Impulse](https://studio.edgeimpulse.com/public/358263/latest). Rileva tre movimenti del telefono cellulare:
- inattività: se lo si tiene in mano rivolto verso l'alto senza muoverlo molto
- S: se si disegna una S in aria, tenendolo rivolto verso l'alto
- O: se si disegna una O nell'aria in senso antiorario.

Per ulteriori informazioni, consultate
- [https://docs.edgeimpulse.com/docs/pre-built-datasets/continuous-gestures](https://docs.edgeimpulse.com/docs/pre-built-datasets/continuous-gestures)
