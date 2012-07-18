# lesson 8

There's been a bit of a break since I've been recording my lesson plans. The scratch club hasn't stopped – in fact it's gone from strength to strength and we've even started a second club!

In the first half of term I got the kids playing with [WeDo](http://info.scratch.mit.edu/WeDo) — a LEGO kit that plugs in to Scratch to provide some simple interactions with the physical world. They really enjoyed it, but it was tricky finding activities that made use of just one WeDo kit amongst six kids, and that could be completed in 45 minutes.

For the second half of the summer term, I've been running pilot sessions for [CodeClub](http://codeclub.org.uk/). The ideas are brilliant and they come complete with full lesson plans and step by step instructions for the kids. If you're thinking of setting up a programming club in your school, please get in touch with them!

For the final session of the term, I thought I'd try something a bit different…

Scratch has a built-in network system that just requires [a little hacking](http://wiki.scratch.mit.edu/wiki/Mesh#Mesh_by_Modification_of_Scratch) to reveal.

Inspired by the [Rube Goldberg WeDo activity](http://scratched.media.mit.edu/resources/physical-digital-chain-reaction-using-wedo-robotics-scratch), I decided to try a software-only version with the kids writing short animations that would run in sequence by sending broadcast events from one computer to the next.

The lesson didn't quite go to plan. What with issues with the school laptop firewall software, one laptop losing its network hardware, and the kids' tendency to fire off the broadcasts to each other all the time, we didn't manage to test them running all together.

If I were running the session again, this is how I would do it (isn't hindsight wonderful!):

1. set up all the kids' computers with Mesh ahead of time
  * bring along an unlocked (un-firewalled) computer and set it up as a Mesh host
  * join all the kids' computers to the host
  * make sure each of the kids' computers can see a variable on the host (there could still be networking problems…)
  * if you do it this way round, you shouldn't run into any issues with firewall software on the kids' computers
1. show the kids a video of a Rube Goldberg machine (I used <http://www.youtube.com/watch?v=qKpxd8hzOcQ> — they loved it and wanted to play it again!)
1. get them to write short animations that start with "on green flag pressed" and that finish after a few seconds
  * suggest that the animation starts on the left side of the screen and finishes on the right hand side
  * suggest that the animation should reset itself at the beginning if it needs to
  * at this point, **don't use broadcasts!**
  * make sure the animations finish and don't loop forever
1. once they've built short animations, get them to add a "broadcast" block at the end of their animation, choosing a single word message to broadcast
1. now tell the kids to stand up and high five each other in sequence, saying their single word message as they do so
  * if you want to, get the last kid in line to run round and high-five the first one to get the animation going in a circle
1. now get them to replace their "on green flag pressed" with "when I receive <event>", making sure to enter the broadcast message word that they received from person to the left of them
1. start the animation on the left side by clicking the script to manually launch it
1. stand back and watch!
