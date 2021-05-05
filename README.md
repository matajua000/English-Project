# Welcome to GitHub Pages

This page holds the program that I made for my english project. Click on the link to start. The program will tell you how to start


## [Link For English Program](https://github.com/matajua000/English-Project/blob/main/EnglishProgram.html)

### Below is all the code in Javascript

  <html>
    <head>
      <script>
        var languages = [
               "Who is Elon Musk?", "Elon Musk is considered to be one of the richest persons in the world due to his influence in many companies that are considered to be the future. He is originally from South Africa. He would later move to Canada to avoid being drafted into the military. He would get his Canadian citizenship as well as his American citizenship. He also studied at many universities like Stanford, UPenn, and Queen's University in Canada. He mainly started by selling the company that he and his brother started Paypal. He would use this money to start his other companies like Space X. Furthermore, he is even considered to be the real-life Tony Stark. His biggest plan is to make space travel accessible to everyone. He is also trying to make it so that life is possible on Mars.",

               "Why is he a hero?", "I would consider Elon Musk to be considered an American hero because of what he had been able to accomplish and what he has planned for the human race. Considering that he came from a different country and he is now considered to be one of the richest persons in the world is quite a journey. He has been a big influence on me, he is considered to be an engineer, and what he has done has influenced me to study mechanical engineering. Furthermore, Musk has shown that a lot of things are possible like running multiple companies at the same time. He runs Tesla, The Boring Company, Space X, Neuralink, and others. He is able to do this and he is also able to balance taking care of all his children. Elon Musk is a hero because he influences the youth and he is also trying to save lives by making space craft accessible to others and allowing us to colonize other planets like Mars.",

               "The Boring Company", "This is one of Musk's newer companies, this company is meant to digging and building tunnels, so that the traffic can be reduced, at the moment they are only digging in Los Angeles since that is where Musk lives. Recently they got a contract from Las Vegas to dig a tunnel under Las Vegas, the tunnel is meant to transport people underground, they plan on using shuttles. The Boring Company also sells they merchandise like cup, mugs and also a flamethrower. The tunnel that is under LA is meant to be used by Tesla cars, they go to a car elevator and are lowered into the tunnel and they are able to travel faster than the cars that are above ground.",

               "Space X", "I think that Space X is a company that everyone knows about since it has been in and out the news about how Musk plans on using Space X to make space travel very accessible to everyone since he is planning to colonize other planets. This company started in 2002, he used the money that he got from selling his previous company to start it. Soon they were able to get a contract from Nasa to transport cargo to the space station. in 2012 Space X launched its first rocket and it was a success. Recently they are working on making rockets reusable before the rockets would detach from the shuttle and fall to the ground but Space X is working on having the rockets land perfectly so that they are able to be used again. This is all part of making space travel cheaper and more effective.",

               "Neuralink", "This company was launched in 2017 and it is considered to be the future. This focuses on trying to fix neurological problems that people might have and it also works on connecting people's minds to technology. this works by implanting a small chip into your skull that would then connect to your smartphone or to any device via Bluetooth. With the help of something, like a bionic eye and the Neuralink scientist predict that they are going to be able to cure blindness using the Neuralink since it will allow humans to be able to communicate with technology. Musk says that the chip is meant to help humans be able to compete with how fast AI is developing. I think that this is one of the cooler companies since I think that it would be interesting to see what is going to follow the Neuralink",

               "Tesla","Tesla is probably the most popular company that Musk runs since you can see the products rolling down the street almost every day. This company was formed in 2003 and it is meant to make gas-powered cars obsolete by having all of the cars be electric. Before there was not much thought in having cars be electric but now more and more car companies are having some cars be electric and Tesla is the front runner of them. Not only do their cars have some of the best safety features it also allows for some self-driving which is pretty impressive because the cars are able to detect accidents happing and act appropriately to make sure that the passengers are safe. Tesla also has semi-trucks which are meant to replace traditional semi-trucks. There is even a Tesla in space when Musk launched his personal vehicle in space. "

           ]
           function changeLanguage(lang, words){
                document.getElementById("h1").innerHTML = languages[lang];
                document.getElementById("p1").innerHTML = languages[words];
              }

      </script>
      <button onclick="StartGame()">Start Game</button>
    </head>

    <body>
      <h1 id="h1">What Company Do You Want to Know About?</h1>
      <p id="p1">Click a Company below</p>

      <span onclick="changeLanguage(0,1)">Who is Elon Musk?</span> -||-
      <span onclick="changeLanguage(2,3)">Why is he a hero?</span> -||-
      <span onclick="changeLanguage(4,5)">The Boring Company</span> -||-
      <span onclick="changeLanguage(6,7)">Space X</span> -||-
      <span onclick="changeLanguage(8,9)">Neuralink</span> -||-
      <span onclick="changeLanguage(10,11)">Tesla</span>
      <script>
      function StartGame(){
        var welcolme
    welcolme="Welcolme to the Build-A-Musk World"

  var intro
    intro="You have chosen to live the life of Elon Musk. You must choose what you are going to do in order to make sure that you end up like the current Elon Musk. If at any point you feel like you have messed up just refresh the page and you will be given another chance."
  var waring
    warning="To play the game you have to think about what actions you should take in order for you to become Elon Musk. "


    var user_quit;
      user_quit = false;




    alert(welcolme);
  	var user_play;


  user_play = confirm("Do you want to play?");



  	if (user_play ==true){
      alert(intro)
      alert("Lets Make an Elon Musk");
      q1 = confirm("Do you think that you should sell Paypal");

      if (q1 ==true) {
      	q2 = confirm("Congradulations you are correct. Next do you think that you should go to Canada?");
        if (q2 ==true){
          q3 = confirm("Correct, only 2 more. Do you move to America?")
          if (q3 ==true){
            q4= confirm("Nice Last One. Should we colonize Mars?")
            if (q4 ==true){
              Final= alert("Congrats you made Elon Musk")
            }
            else{
              alert("Congrats, you won you can refresh to play again")
            }
          }
          else{
            	alert("Well, you were given the option. I thank you for at least taking a look at the program that I made.");
          }
        }
      }

      else{
        	alert("Well, you were given the option. I thank you for at least taking a look at the program that I made.");
      }
  	}
  	else {
    	alert("Well, you were given the option. I thank you for at least taking a look at the program that I made.");
  	}




  }
      </script>
    </body>

</html>

