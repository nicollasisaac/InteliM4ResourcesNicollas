void setup()
{
  pinMode(10, OUTPUT);
}

void loop()
{
  digitalWrite(10, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(10, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

/* LED Vermelho:
A diferença de tensão entre a fonte de 5V e o LED vermelho de 2V é a tensão através do resistor:
V = 5V - 2V = 3V
Usando a fórmula U = R x I, onde a corrente típica para muitos LEDs é de 20mA (0,020A), temos:
3V = R x 0,020A
R = 3V ÷ 0,020A = 150 ohms */