//Adding-new-Java-Frame

 
 
 
 
 
 
 
 
 
 
 private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
     String s=t1.getText();
     String pass=new String(t2.getPassword());
     if("xyz".equals(s) && "xyz@123".equals(pass))
     {JOptionPane.showMessageDialog(null,"Hurrah!! logged in");
     
     NewJFrame2 n=new NewJFrame2();
     n.setVisible(true);
     n.setBounds(0, 0, 1000, 500);
     
     
     }
     else JOptionPane.showMessageDialog(null,"Invalid username or password");
     
     
     
    }       
