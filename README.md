import java.awt.*;
import javax.swing.*;
import java.awt.event.*;
    public class Soso {
    
        public static void main(String[] args) {
            // Create application frame.可加外观风格
            JFrame frame = new JFrame("Welcome Soso Calculator!");//创建窗口对象
            
            frame.setSize(400,400);
            frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
            
            //性别选择框
            JPanel contentPane = new JPanel();//创建面板对象
            ButtonGroup bg = new ButtonGroup();//创建单选按钮组
            JButton male = new JButton("男");
            JButton female = new JButton("女");
            bg.add(male);
            bg.add(female);
            contentPane.add(male);
            contentPane.add(female);
           
       
           
          
        
            // Show frame
            frame.setVisible(true);
    }
}
