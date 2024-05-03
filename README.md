import java.awt.Color;

public class Exemplo {

    static public void main(String[] args) {

        int i = 0;

        Circle circ1 = new Circle();
        Circle circ2 = new Circle();
        Circle circ3 = new Circle();
        Circle circ4 = new Circle();
        Circle circ5 = new Circle();
        Circle circ6 = new Circle();
        Circle circ7 = new Circle();
        Circle circ8 = new Circle();
        Triangle tri1 = new Triangle();
        Square squa1 = new Square();
        Square squa2 = new Square();
        Square squa3 = new Square();
        Square squa4 = new Square();
        Square squa5 = new Square();

        circ1.makeVisible();
        circ1.changeSize(70);
        circ2.makeVisible();
        circ2.changeSize(70);
        circ3.makeVisible();
        circ3.changeSize(40);
        circ4.makeVisible();
        circ4.changeSize(40);
        circ5.makeVisible();
        circ5.changeSize(20);
        circ6.makeVisible();
        circ6.changeSize(20);
        circ7.makeVisible();
        circ7.changeSize(20);
        circ8.makeVisible();
        circ8.changeSize(20);
        squa1.makeVisible();
        squa2.makeVisible();
        squa3.makeVisible();
        

        // Olhos
        circ1.changeColor("white");
        circ2.changeColor("white");
        circ3.changeColor("blue");
        circ4.changeColor("blue");
        circ5.changeColor("black");
        circ6.changeColor("black");

        // Corpo
        squa1.changeColor("yellow");
        squa1.changeSize(160);

        // Calças
        squa2.changeColor("black"); // Cinza
        squa2.changeSize(160);
        squa2.moveDown();
        squa2.moveDown();
        squa2.moveDown();
        squa2.moveDown();
        squa2.moveDown();
        squa2.moveDown();
        squa2.moveDown();
        squa2.moveDown();

        squa3.changeColor("black"); // Marrom
        squa3.changeSize(160);
        squa3.moveDown();
        squa3.moveDown();
        squa3.moveDown();
        squa3.moveDown();
        squa3.moveDown();
        squa3.moveDown();
        squa3.moveDown();
        squa3.moveDown();

        // Bochechas
        circ7.changeColor("red");
        circ8.changeColor("red");
        circ7.moveDown();
        circ8.moveDown();
        circ7.moveDown();
        circ8.moveDown();
        circ7.moveDown();
        circ8.moveDown();
        circ7.moveDown();
        circ8.moveDown();
        circ8.moveRight();
        circ8.moveRight();

        // Dentes
        squa3.changeColor("white");
        squa3.changeSize(20);
        squa3.moveRight();
        squa3.moveRight();
        squa3.moveUp();
        squa3.moveUp();
        squa3.moveUp();

        
        
        

        // Loop para mover os objetos
        while (i < 1) {
            squa1.moveRight();
            squa2.moveRight();
            squa3.moveRight();
            i++;
        }
        while (i < 4) {
            circ1.moveRight();
            circ3.moveRight();
            circ5.moveRight();
            circ7.moveRight();
            i++;
        }
        while (i < 11) {
            circ2.moveRight();
            circ4.moveRight();
            circ6.moveRight();
            circ8.moveRight();
            i++;
        }

    }
}
