# Login-Form
import javax.swing.JOptionPane;

private void loginBtnActionPerformed(java.awt.event.ActionEvent evt)
{
   String uid=uidTF.getText();
   String per=newString(pwdPF.getPassword());
   if(uid.equals("Ashwathi"))
{
   if(pwd.equals("12345")
         JOptionPane.showMessageDialog(null,"Login Successful");
   else
         JOptionPane.showMessageDialog(null,"Wrong Password");
}
   else
  {
     JOptionPane.showMessageDialog(null,"Login Failed!Invalid User ID or Password");
  }
}

private void clearBtnActionPerformed(java.awt.event.ActionEvent evt)
{
    uidTF.setText(null);
    pwdPF.setText(null);
}

private void exitBtnActionPerformed(java.awt.event.ActionEvent evt)
{
    System.exit(0);
}
