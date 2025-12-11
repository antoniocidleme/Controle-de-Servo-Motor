# Controle-de-Servo-Motor
Uso de micro controlador para controle de servo motor

Os códigos deste repositório foram feitos para controlar servo motores usando ESP32 ou Arduino Uno a partir da linguagem C++.

No projeto realizado, os servos foram usados para mover pás a partir de um braço mecânico para gerar pequenas ondulações em uma piscina.

Na versão para ESP32, o código gera uma página em html como interface gráfica para o controle dos servos. Esta página pode ser acessada via o WiFi cujo o nome e senha estão declarados no início do código.

A versão para Arduino Uno é uma versão simplificada que conta apenas com a lógica de controle dos servos usando apenas a função millis(), sem o uso de delay(), para não travar o funcionamento geral do programa enquando os servos se mexem. Esta versão não tem interface gráfica e os valores das variáveis só podem ser ajustados recompilando o código.
