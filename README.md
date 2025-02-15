# Animals social behaviors

Animals exhibit a variety of social phenomena that mirror human behaviors in interesting ways. Here are some examples:

1. Altruism & Cooperation
  - Vampire Bats: Share blood meals with others that failed to feed, ensuring survival within the colony.
  - Meerkats: Take turns standing guard while others forage, warning the group of predators.
2. Hierarchy & Leadership
- Wolves: Operate in packs with an alpha pair leading the group.
- Elephants: Matriarch-led herds where older females guide the group based on experience.
3. Collective Intelligence & Swarm Behavior
- Ants & Bees: Work as superorganisms, making complex group decisions without a central leader.
- Fish Schools & Bird Flocks: Move in synchronized formations to evade predators.
4. Culture & Traditions
- Chimpanzees: Pass on tool-making skills across generations (e.g., using sticks to extract termites).
- Dolphins: Teach young unique hunting techniques, like using marine sponges as protection when foraging.
5. Social Punishment & Justice
- Rhesus Macaques: Punish members that steal food or break social norms.
- Elephants: Show resentment or revenge behavior against individuals that harmed them.
6. Mating Strategies & Courtship Rituals
- Peacocks: Use extravagant tail displays to attract mates.
- Bowerbirds: Build intricate nests and decorate them to impress potential mates.
7. Grief & Mourning
- Elephants: Show mourning behavior, gently touching the bones of deceased relatives.
- Dolphins & Whales: Carry dead calves for days, indicating emotional attachment.

## Bird murmuration behaviour
Murmuration in birds, falls under Collective Intelligence & Swarm Behavior. It happens when large groups of birds, usually starlings, fly together in coordinated patterns, creating mesmerizing, fluid shapes in the sky. The movement looks almost like a living wave or a shifting cloud.
Thousands of starlings create mesmerizing aerial formations *without a leader*, adjusting based on their nearest neighbors.
Each bird follows simple rules (stay close but not too close, align with others), forming self-organizing patterns.

![BirdMurmuration](Bird_murmuration.gif)

## Learning rules 
Here, I developed a multi-agent reinforcement learning (MARL) algorithm that uses simple rules and I reward them based on those, such as: 
  - Cohesion: Keep the birds in the center of the mass. (v1)
  - Alignment: Maintain their velocity with the average velocity of neighbors. (v1)
  - Separation: Penalize birds for getting too close to each other. (v1)

## Trial
  -  In the very first code, I creatd a 2D environment. 
  -  In my second code, I developed a 3D model. The pattern is not much mesmerizing, yet not that bad, at least they respect the rules.

![BirdMurmuration](Mu_1(2D).gif) ![BirdMurmuration](Mu_1.gif)





