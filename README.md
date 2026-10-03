# Patrick Robinson's Blocz game
## Blocz Home
Play the game of your dreams, right here, it is just 1-click away.  
I know that children like computers, because I am a child, and I would go on 24/7 if I could.
## Steps to download
- Click the option that you need(e.g. the ZIP bundle with the JAR file inside)  
- Run a certain command  
- BOOM! You have downloaded and Launched Blocz
## How to use it
1. Run the command(listed on official site)
2. 
## Thanks
Open a HTML editor and type this in:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Your award</title>
    </head>
    <body>
        <h1 style="font-family:serif">Thanks for downloading Blocz</h1>
    </body>
</html>
```
### Or use this method
* Open a Java editor
*  Create a new file called exactly Main
*  Paste this exact code:
```java
import javax.swing.JOptionPane;

public class Main {
    public static void main(String[] args) {
        // Formatted with basic HTML tags to make it look like a large header
        String message = "<html><h1>Thanks for downloading Blocz</h1></html>";
        String title = "Your award";
        
        JOptionPane.showMessageDialog(null, message, title, JOptionPane.INFORMATION_MESSAGE);
    }
}
```
