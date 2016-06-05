# fire-emblem-matcher
Optimizing character pairings.

### Description

Matching Fire Emblem characters can be complicated -  especially if you care about good supports, the child's hair colour AND making the best possible child unit for combat.

This program is designed to help players out.

###Gale–Shapley algorithm

Inspired by a Hannah Fry book I read, <code>fire-emblem-matcher</code> uses the Gale-Shapley algorithm to make it's matches.

For more info check out the <a href = "https://en.wikipedia.org/wiki/Stable_marriage_problem">Wiki</a>

###Issues

Cannot handle Fire Emblem list:

  <ol>
  <li>For multiple branches of fates <code>propose_to</code> and <code>respond_to</code> methods need to be able to handle non-existent preferences.</li>
  
  <li>Requires full range of preferences but this does not reflect reality where some characters cannot match (ie. Laslow-Sakura or any siblings). May fixed with change to above</li>
  </ol>

###Author

  <ul>
    <li>Rachel Day</li>
  </ul>

###License

  MIT.
  
###Acknowledgements
 
 In addition to my own game-play experience, data on optimizing pairings gleaned from :
 
 <ul>
    <li><a href ="http://fireemblem.wikia.com/wiki/Fire_Emblem_Wikia">Fire Emblem Wikia</a></li>
    <li>Serene Forest <a href = "https://serenesforest.net/wiki/index.php/Fates_Support_Conversations">support conversation database</a> for Fates</li>
    <li>Gamefaqs message boards</li>
    <li><a href ="https://www.reddit.com/r/fireemblem/comments/48u8b4/fe14_optimal_fates_pairings_birthright_conquest/">This fantastic MatLab program </a> created by <a href = "https://www.reddit.com/user/DoctorBandage">DoctorBandage</a> using <a href = "https://www.reddit.com/u/Shephen">Shephen</a>'s pairing guide.
 </ul>
