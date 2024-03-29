## Extra exercises

"If you're here, it means you're not feeling very comfortable with ruby and/or databases. Don't feel bad about it, that is alright. It doesn't mean that you're slow or that programming is not for you, it just means that your learning path is different.

Your batch, the 358, is my 12th batch so far. I had some students before who were completely lost, who spent two weekends practicing stuff and then became extremely confident and comfortable with ruby. And other pretty lost students who, after their batch, spent months studying and then opened their own business - programming everything in them - and became quite rich.

See the difference between two weekends and months? That's because if you practice during the weekends, you can open a ticket on Monday to make questions about what you struggled. But if you only do it **after** the bootcamp has ended, you can't open any more tickets. So you'll be figuring out things by yourself. Use the tickets. Use the teachers. Use the TAs. We are all paid to solve your questions and problems and to help you, so use us!!

And that is not a rule that applies only to LeWagon. I studied computing in university, and I had friends who hated programming basicaly because they didn't get it, and a few years later they were hard-ass coders earning more than me. This is no "coaching crap", it's the truth. Believe it or not :)

So it is, in the end, up to you. Okay? You need to have initiative. I've built this specially for you guys/girls, to try to help you find the confidence that you may have lost somewhere.

If you're okay with that, then let's start! Arm yourself with **PATIENCE**, **FOCUS** and **CONFIDENCE**, it's all that you need to learn how to code.

Important disclaimer: if you get stuck at one exercise, **DO NOT SKIP IT**. Send me messages on Slack and I'll help you."

_original message from Matheus Penchel to batch-358_

To start, run the following in the terminal: 

```zsh
export GITHUB_USERNAME=`gh api user | jq -r '.login'`
echo $GITHUB_USERNAME
cd ~/code/$GITHUB_USERNAME
git clone git@github.com:dedemenezes/practicing-ruby-out.git
```

And then hop into the `practicing-ruby-out` folder!
