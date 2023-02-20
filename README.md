# SaraKIT_Basics

## BLDC Encoder and two synchronized gimbals

![SaraKIT_field_oriented_control_FOC](https://user-images.githubusercontent.com/35704910/220133540-a8d33283-8703-42f1-8bd1-8213652b9dcb.gif)

Using Raspberry PI with SaraKIT, AS5048A Encoder with Brushless Motor Controllers (BLDC)

This demo shows how to use one of the encoders (e.g. AS5048A, AS5600) with SaraKIT and Raspberry PI CM4 to control another gimbal in a synchronous manner.
By turning the gimbal in which the encoder is, I rotate the second gimbal in the same way.
Of course, you can use the AS5048A decoder itself by connecting it via PWM to one of the two connectors on the SaraKIT board.

```bash
git clone https://github.com/SaraEye/SaraKIT-AS5048A-AS5600-encoder-Raspberry-Pi EncoderDemo
cd EncoderDemo
make
./gimbals
```

this is exactly that part of the movie: https://youtu.be/Nwvnoo5efzE?t=607

## A Guide to Using BLDC Motors (Gimbals) with SaraKIT: A Comparison of Stepper Motors, Servos, and BLDC Motors:

[YouTube Video about SaraKIT and BLDC driver](https://youtu.be/Nwvnoo5efzE)


[https://SaraKIT.SaraAI.com](https://SaraKIT.SaraAI.com)

