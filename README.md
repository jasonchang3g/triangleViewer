import javax.swing.JFrame;

/**
   This program displays a rectangle that can be moved with the mouse or keyboard.
*/
public class TriangleViewer
{  
   public static void main(String[] args)
   {        
      JFrame frame = new Triangle();
      frame.setSize(500, 500);
      frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
      frame.setVisible(true);
   }
} 
