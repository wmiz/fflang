<script>
  // Array of parent testimonials with separated highlight and body
  const parentTestimonials = [
    {
      highlight: "They are already speaking in complete sentences!",
      body: "<highlight>My kids started this Spanish class with very little vocabulary and they are already speaking in complete sentences, and I’m kind of amazed.</highlight> It seems they are progressing a lot faster in this manner than they did before because it’s a lot more interactive than Duolingo, Mango lessons or workbooks and they didn’t seem to remember it and they weren’t progressing very well and they decided to stop.",
      author: "Anne Chmura (Homeschooling Mom)"
    },
    {
      highlight: "I’ve been amazed at what they can say and understand in Spanish!",
      body: "My kids have had a great time in this fun and fast-paced Spanish class. <highlight>I've been amazed at what they've been able to say and understand in Spanish after only a few weeks!</highlight> I'm excited for the next class.",
      author: "Emily Heilman (Homeschooling mom)"
    },
    {
      highlight: "You can study books and rules and never be able to have a conversation, Reed is teaching them conversation from the beginning.",
      body: "Reed leads Spanish in such an interactive way! She is silly and has fun, which engages the kids. <highlight>The class begins with Reed speaking and the class following, and then as they advance they start speaking naturally, just like we learn language as babies. You can study books and rules and never be able to have a conversation, Reed is teaching them conversation from the beginning.</highlight> My kids have learned a lot over the summer, and what is best is that they now have fun speaking Spanish and looking up new vocabulary on their own! We are excited for the next class!",
      author: "Camila Whitman (Homeschooling mom)"
    },
    {
      highlight: "After even just one class, I could tell that my daughter was engaged.",
      body: "As a parent, I wasn’t sure what to expect from the class, <highlight>but after even just one class, I could tell that my daughter was engaged and it was easy to follow along for her, and lots of notes were given for review and the interactive readings were easy to do in between classes and i really felt it was worth the time and money that we invested in it.</highlight>",
      author: "Jolene Knoll-Fasse (Homeschooling mom)"
    },
    {
      highlight: "This is the way languages should be taught!",
      body: "Senora Goodey has been an absolute gem! I am so grateful to have had my daughter enrolled in her Spanish class. <highlight>I have been absolutely astonished by how quickly my daughter has picked up on the language. This is the way languages should be taught!</highlight> My daughter has expressed to me that she will never forget what she has learned, because of how much fun she has had both listening to and creating the stories that this class provides.",
      author: "Tabitha S. (Homeschooling mom)"
    },
    {
      highlight: "Reed is an awesome, fun, patient, teacher!",
      body: "We absolutely loved Foundational Flow, Spanish 1 class with Reed Goodey! <highlight>As the parent, I loved the amount of dedication and time Sra. Goodey put into every single session. I love that Sebastian (age 10) would immediately want to tell me everything about class and what he learned. I couldn’t believe he was reading Spanish and knew exactly what he was reading!</highlight> I’m grateful that for how Reed is an awesome, fun, patient, teacher! Because of that, our son has learned a second language and really enjoyed doing it! We look forward to another class with Sra Goodey.",
      author: "Meaggan L. (Homeschooling mom)"
    },
    {
      highlight: "I would absolutely recommend her class!",
      body: "Alaina and I have been taking Reed's Online Spanish class and really enjoyed her teaching style. It is so fun to learn with my daughter and laugh while we try out our Spanish on each other and on Reed. I would absolutely recommend her class to anyone wanting to learn Spanish.",
      author: "Jennifer M. (Homeschooling mom)"
    },
    {
      highlight: "It’s pretty amazing that I didn’t get any resistance from my kids. They’re all onboard to keep learning.",
      body: "As a parent, it’s pretty amazing that I didn’t get any resistance from my kids. They’re all onboard to keep learning.",
      author: "Mary W. (Homeschooling mom)"
    },
    {
      highlight: "My son has never been so inspired to learn before!",
      body: "Reed G. is a fantastic teacher!!! My son has never been so inspired to learn before. We highly recommend her.",
      author: "Debra D. (Homeschooling mom)"
    },
    {
      highlight: "At the end of their first class they said: “That was the most fun we’ve ever had in a class!”",
      body: "This summer my two boys took Reed Goodey’s 8 Week Spanish class. At the end of their first class they said: “That was the most fun we’ve ever had in a class!” And they enjoyed every class after that as well! Learning Spanish through Reed’s method of teaching was so fun for my boys, and worked! They have learned so much! Her method puts the kids into real life situations and interactions with the Spanish language through role play and games, and I feel that’s what helped my kids learn so fast. The ‘homework’ was easily accessible and another fun way to put what they have learned into practical use. The boys ‘practiced’ what they’ve learned on each other, even their little sister was picking things up! Mrs. Goodey is also just a fun, energetic, wonderful teacher and my kids really enjoyed her! I highly recommend this class!",
      author: "Bianca N. (Homeschooling mom)"
    },
    {
      highlight: "We were surprised that we were speaking Spanish.",
      body: "My son and I had an awesome experience with Reed as our Spanish teacher. She knows the language very well, and has a fun way of teaching it. She has a way of teaching that is both engaging and effective. After taking the classes, we were surprised that we were speaking Spanish. We plan on starting the lessons again as soon as school starts. I highly recommend Mrs. Reed as a Spanish teacher.",
      author: "Terri H. (Homeschooling mom)"
    },
    {
      highlight: "Reed was a fabulous teacher for my 15 year old son.",
      body: "Reed was a fabulous teacher for my 15 year old son for Spanish. He learned a lot and had a fun time too. She was super helpful to motivate him to learn and also practice conversational Spanish. I feel like my son was really lucky to have Reed’s help and engaging learning. I am sure that if you want a great Spanish teacher you would really like her too.",
      author: "Leslie H. (Mother of Student)"
    },
    {
      highlight: "She made the learning fun and easier!",
      body: "Reed helped my daughter learn Spanish in such a friendly and efficient manner. She even had tips that made the learning fun and easier! She is an excellent teacher and we recommend her highly.",
      author: "Kira C. (Homeschooling Mom)"
    },
    {
      highlight: "All 3 said she is the best teacher they’ve ever had.",
      body: "My children have thrived under her teaching, all three said she is the best teacher they have had because not only does she make it fun; they can also retain the information. She uses many different methods so even though my three kids learn differently they have all been able to learn at the same level of understanding. After class, they are laughing and all talking in Spanish.",
      author: "Sarah G. (Homeschooling mom)"
    },
    {
      highlight: "I can’t say enough wonderful things about this class.",
      body: "My son (14) and my daughter (11) took the Spanish foundational 1 class from Senora and both loved the class. My son is shy and does not like class participation, but he finished every class smiling with stories about something that he enjoyed during class. I cannot say enough wonderful things about this class or Senora Goodey. She genuinely enjoys teaching children and it shows.",
      author: "Connie C. (Homeschooling mom)"
    }
  ];

  // Array of student testimonials with separated highlight and body
  const studentTestimonials = [
    {
      highlight: "My cousin is pretty fluent in Spanish, and I was able to hold a pretty good conversation with her because I had the conversation skills from taking this class.",
      body: "Before taking this class, I really didn’t have any linguistic skills in Spanish at all, and I was at my cousin’s a couple of weeks ago, <highlight>and my cousin is pretty fluent in Spanish, and I was able to hold a pretty good conversation with her because I had the conversation skills from taking this class, and I thought it was really cool.</highlight> Also, I just finished the last Spanish class today, and I just texted a friend who’s in AP Spanish, actually in Spanish, and be able to hold a conversation with her.",
      author: "Izzy F. (age 14) Student"
    },
    {
      highlight: "As someone who’s been struggling with dyslexia…after just a couple of weeks, I’m able to read…probably better than I can read English!",
      body: "<highlight>As someone who’s been struggling with dyslexia, this program has been very helpful for me, cause there’s a lot of reading and there’s a lot of spelling, and I’ve been able to read whole paragraphs in a completely different language.</highlight> I’ve been able to read on my own, and it’s amazing to me to see that after just a couple of weeks, I’m able to read…probably better than I can read English!",
      author: "Tess D. (age 15) Student"
    },
    {
      highlight: "It’s very fun learning!",
      body: "I was very surprised and it’s very fun learning, and I like it and I’m learning a lot, and all the games and stories are really fun for me.",
      author: "Mary Grace W. (age 16) Student"
    },
    {
      highlight: "Now I can speak in full sentences!",
      body: "I was so blown away when, before the class, my mom was reading about what this class is, I didn’t think that we were actually going to be able to speak, and now I can speak in full sentences, and we’re not even done with the class yet, and after it’s going to be amazing, and i just didn’t think that would happen in only an hour a week, and a couple of lesson practices.",
      author: "Kate W. (age 15) Student"
    },
    {
      highlight: "I want to take every class she offers.",
      body: "This class was so much fun. She makes me feel like I could learn any or all of the languages that I want to! I want to take every class she offers.",
      author: "Amelia S. (age 11) Student"
    },
    {
      highlight: "I’ve been able to retain what I learn. It’s really easy!",
      body: "I like the stories we create, and it’s fun and adds creativity and I learn the words better and I’m better at telling people things in Spanish cause I can actually remember words. I’ve been able to retain what I learn from this class and I enjoy the level of creativity that is brought out in the class. It’s really easy! I know I understand all that is said and so much more than I thought I would, so it’s pretty impressive.",
      author: "Leonida B. (age 14) Student"
    },
    {
      highlight: "I love this way of learning!",
      body: "I love this way of learning because you get to learn at your own speed, and it’s interactive with the stories.",
      author: "Lily C. (age 12) Student"
    },
    {
      highlight: "I was like blown away that I could actually speak Spanish!",
      body: "I was like blown away that I could actually speak Spanish and talk in Spanish, because before that I basically had no idea how to speak Spanish.",
      author: "Maggie C. (age 11) Student"
    },
    {
      highlight: "After only 4 classes, I can now speak, read, and understand basic Spanish!!",
      body: "After only 4 classes, I can now speak, read, and understand basic Spanish!! And it’s really fun!",
      author: "Garvon G. (age 14) Student"
    },
    {
      highlight: "I had a Spanish teacher before who taught completely differently and I came away with nothing.",
      body: "I had a Spanish teacher before who taught completely differently and I came away with nothing. There are many activities we do in Spanish with a target set of vocabulary that makes me learn and remember the context easily. After Sra’s class, I feel confident to hold a conversation with anyone in Spanish.",
      author: "Kolby D. (age 16) Student"
    },
    {
      highlight: "I’m really amazed that I got this good at it this fast.",
      body: "Well, I’m really amazed that I got this good at it this fast and learned all these words!",
      author: "Daniel W. (age 12) Student"
    },
    {
      highlight: "I can understand Spanish when it’s spoken at movies/shows, and in my family when my grandpa speaks.",
      body: "The interactive activities in this method have made it so much easier to learn. It benefitted me because I can understand Spanish when it’s spoken at movies/shows, and in my family when my grandpa speaks.",
      author: "Claire W. (age 14) Student"
    },
    {
      highlight: "I learned in a few short weeks in Sra’s class more than a whole year in another class.",
      body: "I learned in a few short weeks in Sra’s class more than a whole year in another class.",
      author: "Tom S. (age 17) Student"
    },
    {
      highlight: "I can express myself and pull words from my brain pretty easily now.",
      body: "Sra. puts a lot of passion and time into our learning to make sure we enjoy each class. I think her method of teaching is easy to understand and memorable and I can express myself and pull words from my brain pretty easily now.",
      author: "Maia R. (age 15) Student"
    },
    {
      highlight: "I’m really surprised at how well I can read.",
      body: "I’m really surprised at how well I can read the Garbanzo’s, all about turtles, dogs, artists, all those things. That would have seemed really hard a while ago, but now I can actually read them!",
      author: "Elizabeth C. (age 11) Student"
    },
    {
      highlight: "The Spanish taught in this method avoids the technicalities of other courses and enables you to apply it and use the language.",
      body: "The Spanish taught in this method avoids the technicalities of other courses and enables you to apply it and use the language. I was not sure of what to expect, but I am pleasantly surprised about how much I know now.",
      author: "Isaac T. (age 17) Student"
    },
    {
      highlight: "I am speaking full sentences with ease.",
      body: "I learned unexpectedly faster than I thought. Now, I am speaking full sentences with ease.",
      author: "Gavin R. (age 17) Student"
    },
    {
      highlight: "Senora is spunky and energetic and it’s a fun class with creative ways to learn.",
      body: "What I’ve learned in this class is so much more than I thought. I am definitely farther along with understanding Spanish than I thought I would ever be. I can speak full paragraphs and explain my feelings and understand what others say. Senora is spunky and energetic and it’s a fun class with creative ways to learn.",
      author: "Emilia M. (age 14) Student"
    },
    {
      highlight: "It’s not boring powerpoints or drills, rather it’s more various fun activities.",
      body: "By the class being more engaged and less English dependant, I believe that learning Spanish has been easy. It’s not boring powerpoints or drills, rather it’s more various fun activities. Sra. has made the class very enjoyable and friendly from the fun story activities to the various games.",
      author: "Kira W. (age 16) Student"
    },
    {
      highlight: "Learning has been so much easier than I ever thought it would be.",
      body: "I learned faster than I thought I ever could and I think it’s because of all the real life stories, and also because it was fun, the class was never dull and it has been a fun process, and learning has been so much easier than I ever thought it would be.",
      author: "Dorian S. (age 17) Student"
    },
    {
      highlight: "I’ve advanced at astronomical levels.",
      body: "Previously, I learned like 3 words, and I feel like now I assumed I wouldn’t be good at language and at my job this summer I was able to talk through a transaction in Spanish with a customer who only spoke Spanish! I genuinely enjoy learning Spanish and I think it’s fun.",
      author: "Keigan B. (age 16) Student"
    },
    {
      highlight: "I could really learn fast this way.",
      body: "Instead of learning about individual words, I am actually speaking in full sentences and now, I can actually speak Spanish. In the start of the first class, it seemed overwhelming as the class is all in Spanish, but as the class went on, it got easier and I found I could really learn fast this way. In fact, I decided to go to a Catholic mass all in Spanish and it was a big surprise to me when I could understood pretty much all of it!",
      author: "Peter C. (age 14) Student"
    },
    {
      highlight: "It’s not drills, rather it’s all verbal and it works, it really does.",
      body: "It’s not drills, rather it’s all verbal and it works, it really does. I learned more in this class than in Duo Lingo, and whatever other program my mom gave me to learn.",
      author: "William G. (age 14) Student"
    },
    {
      highlight: "I learned more by the end of the month than I learned in a previous year!",
      body: "I learned more by the end of the month than I learned in a previous year in a school!",
      author: "Holden G. (age 15) Student"
    },
    {
      highlight: "I hardly knew anything at the start and now I know a lot!",
      body: "I hardly knew anything at the start and now I know a lot! I was able to comprehend and speak a lot of Spanish I never knew. I learned a lot in such a short time. I think it is easy to learn and I am impressed at my knowledge. I can kind of show off by translating different words and saying things for fun in Spanish.",
      author: "Preston O. (age 14) Student"
    },
    {
      highlight: "It was super fun with all the stories and games that made you talk.",
      body: "Spanish was way easier than I thought because it was super fun with all the stories and games that made you talk. Now when I see Spanish on TV, I can translate it! I really do think I understand Spanish to a good intermediate level and this is my first class.",
      author: "Sloane K. (age 14) Student"
    },
    {
      highlight: "She was super understanding, patient and comforting as a teacher.",
      body: "Reed Goodey taught me online in such a fast and fun way and within just weeks we were able to improve my communicative abilities by making humorous and comical stories with characters. As well, she was super understanding, patient and comforting as a teacher and taught me in a caring way.",
      author: "Sasha P. (age 15) Student"
    },
    {
      highlight: "The class has been more interactive than any Spanish apps.",
      body: "The class has been more interactive than any Spanish apps I have tried to learn with, and I learned more here than with others ways.",
      author: "Connor R. (age 15) Student"
    },
    {
      highlight: "Now I can actually understand and speak the language.",
      body: "I thought I would never be able to learn anything in Spanish and now I can actually understand and speak the language.",
      author: "Hannah H. (age 14) Student"
    },
    {
      highlight: "I was so surprised by how much I learned!",
      body: "I was so surprised by how much I learned and could retain.",
      author: "Madison S. (age 14) Student"
    },
    {
      highlight: "Sra. is one of the most caring teacher I’ve ever had and I’m forever grateful.",
      body: "It has definitely been fun and has been one of my favorite ways to learn with all the Spanish and I have a higher level of ability that I ever thought…I even find myself translating things into Spanish without even thinking that hard about it! As well, Sra. is one of the most caring teacher I’ve ever had and I’m forever grateful.",
      author: "Morgan S. (age 15) Student"
    },
    {
      highlight: "We did a lot of stories which helped a lot!",
      body: "I found it easy to learn as we did a lot of stories which helped a lot for me to learn new words.",
      author: "Anna W. (age 15) Student"
    },
    {
      highlight: "I can speak, read and write well in Spanish which makes me more confident to travel.",
      body: "I liked doing interactive games and activities and I can speak, read and write well in Spanish which makes me more confident to travel.",
      author: "Devyn B. (age 16) Student"
    },
    {
      highlight: "I didn’t think I would ever be able to read Spanish as well as I can.",
      body: "Most of the classes have games and fun stories. I also really enjoy the music. I didn’t think I would ever be able to read Spanish as well as I can. I like to translate the menus at Mexican restaurants.",
      author: "Macy S. (age 16) Student"
    },
    {
      highlight: "I always learn when I’m having fun.",
      body: "I was surprised by how fast I started to understand Spanish. The games and mini stories were fun and I always learn when I’m having fun.",
      author: "Lily W. (age 15) Student"
    },
    {
      highlight: "I can really talk in Spanish!",
      body: "I was expecting to learn words like “Si” and “Hola,” but I have learned whole sentences and much more and I can really talk in Spanish-And I can also read it!",
      author: "Claire K. (age 14) Student"
    },
    {
      highlight: "I have learned to talk very well in Spanish!",
      body: "Sra. helped me learn Spanish in so many fun and also hilarious ways! I have learned to talk very well in Spanish!",
      author: "Megan L. (age 14) Student"
    },
    {
      highlight: "Sra emphasizes playful learning that now I think Spanish is an easy language to learn.",
      body: "I learned so much more than any app could teach me. The interaction and being surrounded in Spanish gets you in a good head space to learn and remember. Sra puts so much effort into every class and in learning about us as well and our learning style and emphasizes playful learning that now I think Spanish is an easy language to learn.",
      author: "Monet S. (age 14) Student"
    },
    {
      highlight: "The way Sra taught made it easy.",
      body: "I can understand and speak a lot more than I ever thought I would..the way Sra taught made it easy.",
      author: "Jace D. (age 15) Student"
    },
    {
      highlight: "I like the games and stories.",
      body: "I like the games and stories because I’m an active learner.",
      author: "Owen P. (age 15) Student"
    },
    {
      highlight: "I can actually say I can read, write, and speak in a spontaneous way!",
      body: "I have learned so much and I can actually say I can read, write, and speak in a spontaneous way. I tried to learning the past and I didn’t learn much at all. This way has been a whole different learning experience.",
      author: "Abby W. (age 16) Student"
    },
    {
      highlight: "I did not expect to be able to read and speak as much as I can.",
      body: "Contributing ideas to a story is fun and it links ideas and memories to words, and it’s fun to talk in Spanish, and I did not expect to be able to read and speak as much as I can.",
      author: "Chris C. (age 14) Student"
    },
    {
      highlight: "Sometimes, I even catch myself thinking in Spanish and it’s fun!",
      body: "I didn’t know any Spanish coming into this class and now I can read, write, and speak at a fully comprehensible level! I feel confident that I can easily have a conversation in Spanish with anyone if I were down in Mexico traveling. Sometimes, I even catch myself thinking in Spanish and it’s fun!",
      author: "Sophia M. (age 17) Student"
    },
    {
      highlight: "I have learned more in this short class, more than in any other way I tried before!",
      body: "Sra. has this way that keeps me engaged, so I want to learn more, and when I want to learn more, I become more focused. I have learned more in this short class, more than in any other way I tried before!",
      author: "Ethan W. (age 14) Student"
    },
    {
      highlight: "I learned faster in this way than just certain vocabulary words on their own.",
      body: "I learned faster in this way than just certain vocabulary words on their own. It’s fun to learn this way because the class was always high energy.",
      author: "Spencer J. (age 14) Student"
    },
    {
      highlight: "I learned much faster than expected and I think it’s because we focused on actually speaking rather than grammar.",
      body: "I learned much faster than expected and I think it’s because we focused on actually speaking rather than grammar. Also, there are songs and I like the Spanish music because it sounds good and it motivates me.",
      author: "Blake E. (age 15) Student"
    },
    {
      highlight: "It’s so much fun that you don’t even realize you’re learning Spanish!",
      body: "I think the reason I am able to learn so much in such a short time is that Sra, uses interactive ways such a stories, games, and activities to help teach her lessons. It’s so much fun that you don’t even realize you’re learning Spanish…It doesn’t feel hard at all!",
      author: "Alex. D. (age 15) Student"
    },
    {
      highlight: "I feel confident that I speak and understand.",
      body: "I learned lots of Spanish and I feel confident that I speak and understand, and the games were fun!",
      author: "Dhruv G. (age 16) Student"
    },
    {
      highlight: "It doesn’t feel like I’m working hard at learning, and the next thing I know, I’m comprehending.",
      body: "I never thought I would be able to comprehend as much as I am able to understand! I thought Spanish would be just memorizing vocabulary, but it was so much different because it doesn’t feel like I’m working hard at learning, and the next thing I know, I’m comprehending.",
      author: "Haley G. (age 17) Student"
    },
    {
      highlight: "It’s immersion Spanish, and no learning through a textbook.",
      body: "It’s immersion Spanish, and no learning through a textbook, so when we are speaking and interacting, I learn the words and vocabulary more quickly…which is so much better cause this way has helped me really learn. I am learning how to speak Spanish to use it on a trip or future career.",
      author: "Alexa S. (age 16) Student"
    },
    {
      highlight: "It feels like you are having fun and not “learning” a whole new language because it doesn’t feel like work, yet I learned so much!",
      body: "In Sra’s class, it feels like you are having fun and not “learning” a whole new language because it doesn’t feel like work, yet I learned so much!",
      author: "Declan D. (age 14) Student"
    },
    {
      highlight: "I love learning in this way. I feel at ease and can say what I want to say.",
      body: "I have been able to say more and more with each class and I love learning in this way. I feel at ease and can say what I want to say.",
      author: "Jason A. (age 16) Student"
    },
    {
      highlight: "This has been such a fun class with all the activities, music, and fun!",
      body: "This has been such a fun class with all the activities, music, and fun and Sra. teaches in a way that’s interesting to me. I love the real life situations and communicating with another person. I also liked learning about other cultures cause it could help me to put myself in other people’s shoes, yet it also challenged my thinking in that way, and gave me more perspective.",
      author: "Shey L. (age 15) Student"
    },
    {
      highlight: "I have learned more than I ever thought I would in one class.",
      body: "I think because this class is more interactive that I have learned way more Spanish than ever did before trying with apps and stuff. Now, I can actually write and say stuff in Spanish. I have learned more than I ever thought I would in one class.",
      author: "Brian B. (age 14) Student"
    },
    {
      highlight: "The way Sra teaches makes it so much easier to learn.",
      body: "The way Sra teaches makes it so much easier to learn. I have learned Spanish so fast because of the fun activities.",
      author: "Athena F. (age 13) Student"
    },
    {
      highlight: "I understand and can speak more than I thought I would.",
      body: "I learned more than I ever expected because of this unique learning style. It’s fun and interactive. I understand and can speak more than I thought I would.",
      author: "Dawson W. (age 13) Student"
    },
    {
      highlight: "The words are put into stories and games, and it gives me a better understanding of the word.",
      body: "I’ve tried in the Pashto Learn Spanish and we never learned the amount of words that I’ve learned in this class, and the words are put into stories and games, and it gives me a better understanding of the word and I don’t forget them I loved creating the stories because I learn vocabulary words with a fun twist to it, and now when I go to other countries I can understand what the people are saying!",
      author: "JD. G. (age 14) Student"
    }
  ];

  // Function to process text and replace  tags with styled spans
  function processText(text) {
  return text.replace(/<highlight>(.*?)<\/highlight>/g, '<span class="bg-yellow-200">$1</span>');
}
</script>

<div class="container mx-auto px-4 py-8">
  <!-- Page Heading -->
  <h1 class="text-5xl font-bold mb-8 text-center">Testimonials</h1>

  <!-- Parents Section -->
  <section>
    <h2 class="text-4xl font-bold mb-4">What Parents Say...</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
      {#each parentTestimonials as testimonial}
        <div class="p-6 bg-white rounded-lg shadow-md">
          <div class="text-lg font-semibold mb-2">“{testimonial.highlight}”</div>
          <div class="text-lg">
            {#each testimonial.body.split('\n\n') as paragraph}
              <p>{@html processText(paragraph)}</p>
            {/each}
          </div>
          <p class="text-sm italic mt-4">- {testimonial.author}</p>
        </div>
      {/each}
    </div>
  </section>

  <!-- Students Section -->
  <section class="mt-12">
    <h2 class="text-4xl font-bold mb-4">What Students Say...</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
      {#each studentTestimonials as testimonial}
        <div class="p-6 bg-white rounded-lg shadow-md">
          <div class="text-lg font-semibold mb-2">“{testimonial.highlight}”</div>
          <div class="text-lg">
            {#each testimonial.body.split('\n\n') as paragraph}
              <p>{@html processText(paragraph)}</p>
            {/each}
          </div>
          <p class="text-sm italic mt-4">- {testimonial.author}</p>
        </div>
      {/each}
    </div>
  </section>
</div>