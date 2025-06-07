A FiveM script that displays useful tips and server command hints to help new and experienced players discover what they can do. Perfect for improving user experience and engagement. Everytime you get on the server another random information appears on the two boxes. You can put your own information on index.html in : 

const tips = [
      'Μπορείς να καλέσεις ταξί με /taxi',
      'Πήγαινε στην τράπεζα με όπλο για να ξεκινήσεις μια ληστεία!',
      'Άνοιξε το inventory με το F2',
      'Γράψε /me στο chat και το μήνυμα που θες!',
       'Χρησιμοποίησε το κινητό σου με το F1 (αν έχεις)'
    ];

You can even put your own server name on index.html in: 


<div class="container">
    <div class="box">
      <div class="title"><i class="fas fa-bullhorn"></i> Gold Premium</div>
      <div class="message" id="tip1"></div>
    </div>
    <div class="box">
      <div class="title"><i class="fas fa-bullhorn"></i> Gold Premium</div>
      <div class="message" id="tip2"></div>
    </div>
  </div>

![Preview](https://github.com/Marios696969/Tips-System-Fivem/blob/main/preview.png?raw=true)
