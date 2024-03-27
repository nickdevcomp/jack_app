
# JACK Drawing Application

Welcome to the JACK Drawing Application! This application allows you to draw on a simulated display using the JACK programming language. It offers intuitive controls and a monitoring dashboard for better user experience.

## Controls

- **Arrows**: Use arrow keys for precise movement across the canvas.
- **S**: Press 'S' to toggle between brush and eraser mode.
- **D**: Press 'D' to enable input (drawing mode). By default, input is disabled to prevent accidental drawing.
- **Z, X**: Press 'Z' to increase and 'X' to decrease the brush size.
- **Q**: Press 'Q' to output your drawing.

## Monitoring Dashboard

On the right side of the application, you'll find a monitoring dashboard. This dashboard provides real-time information about the application's performance, including:

- **Drawing Mode**: Indicates whether the application is in brush or eraser mode.
- **Brush Size**: Shows the current size of the brush.
- **Input Status**: Indicates whether input (drawing) is enabled or disabled.
- **Output Status**: Shows whether any output (drawing) has been saved.

## Getting Started

### Prerequisites

To run this application, you need the JACK programming language environment set up on your system. You can download and install the JACK compiler and simulator from the [official website](https://www.nand2tetris.org/software).

### Installation

1. Clone the repository: git clone https://github.com/nickdevcomp/jack_app
2. Launch app using n2t JVM server

![Пример изображения](https://img.freepik.com/free-photo/computer-program-coding-screen_53876-138060.jpg?t=st=1711358441~exp=1711362041~hmac=b3e1ddc8cc903b89537fc5a7ba27c3fde78da757a342c2556ce379fed28902bd&w=996)

### Review

Овчинников Данила

Крутой проект, который отлично декомпозирован.
Идеи: было бы отлично добавить туда режим курсора, чтобы он ничего не стирал и не рисовал, просто двигался по экрану, что бы можно было начать рисовать с другого места, не включая режим ластика
Просто не красиво(по учебнику Тебайкина М.Д):
1) if (key = 131) {let direction = 1; } - мне кажется это лучше не писать в строчку, будет больше строчек в 3 раза, но мне кажется в джеке так не принято
2)
field int x,y;
field int size;
constructor Eraser new(int x_, int y_, int size_){}
давайте ставить enter между полями и конструкторами и методами
3)конец
