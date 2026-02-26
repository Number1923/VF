# Strange Behaviors Wiki Updates

## Summary
Updated the VortexFoods™ Wiki with comprehensive information from **"Strange Behaviors"** (American Setting, Story 1). This includes adding percentage bars to all characters involved in the story and iconic quotes for each character.

---

## Characters Updated

### 1. **Ashley Taylor** (Predator)

**Percentage Bars Added:**
- **Shrinkie Cravings: 85%** - Buys a full box, eats them casually while studying, enjoys the taste and squirming sensation
- **Cruelty: 25%** - Not particularly cruel; eats matter-of-factly without excessive taunting, though calls Timothy a liar
- **Playfulness: 60%** - Plays with Brian in her mouth for several minutes, primarily to indulge his desires
- **Intimate Behavior: 5%** - Wears revealing clothes but doesn't use shrinkies sexually
- **Supports Vortex/Righteousness: 95%** - Fully believes Vortex is making the world better, philosophically justifies eating "criminals and wastelings"

**Iconic Quote Added:**
> "You're... weird." — Ashley to Brian, Strange Behaviours

**Key Traits:**
- Described as angelic-faced with piercing blue eyes, athletic build, blonde hair
- Studies German in honor of her late grandmother
- Shows curiosity when Brian laughs, pauses to talk with him
- Believes older generation (like her mother) is "misguided" about humanitarian concerns
- Honors Brian's request to be swallowed whole

---

### 2. **Brian** (Shrunken/Prey - Primary POV Character)

**Percentage Bars Added:**
- **Intelligence: 30%** - No escape attempts, doesn't try to reason for freedom
- **Fear: 85%** - Described as terrified, hyperventilating, heart racing, teeth chattering
- **Vocalness: 15%** - Mostly silent, doesn't beg like other shrinkies
- **Obedient: 90%** - Surrenders willingly, asks to be eaten, complies with all requests
- **Desire: 100%** - Vorarephile with uncontrollable erection, aroused beyond words by Ashley

**Iconic Quote Added:**
> "I've been looking forward to this all my life." — Brian to Ashley, Strange Behaviours

**Key Traits:**
- Self-described vorarephile (sexual attraction to being eaten)
- Unemployed "loser" with medical debt from nervous breakdown
- Finds Ashley exceptionally beautiful
- Experiences intense internal conflict: terrified of death but desperately desires it
- Laughs uncontrollably when about to be eaten, which catches Ashley's attention
- Dies from combination of acid burns, drowning in stomach chyme, and physical implosion

---

### 3. **Megan Sanders** (Shrunken/Prey)

**Percentage Bars Added:**
- **Intelligence: 40%** - Was investigating journalist disappearances (smart background), but no escape shown
- **Fear: 95%** - Described as pleading for her life
- **Vocalness: 85%** - Pleads for her life mid-sentence as Ashley swallows her
- **Obedient: 10%** - Actively resisting, trying to escape, pleading
- **Desire: 0%** - No indication of attraction to Ashley

**Iconic Quote Added:**
> "[Pleading for her life mid-sentence as Ashley swallows her]" — Megan Sanders, Strange Behaviours

**Key Traits:**
- Lawyer investigating cold cases of disappeared journalists
- Drew ire of both Department of Justice and VortexFoods™
- First shrinkie Ashley consumes in the story
- Eaten casually during patio furniture assembly with Ashley's mother
- Narrative notes that nobody will ever hear about her or the journalists she investigated

---

### 4. **Timothy Walker** (Shrunken/Prey)

**Percentage Bars Added:**
- **Intelligence: 20%** - Lies claiming innocence, which Ashley sees through immediately
- **Fear: 90%** - Begging for his life, claiming he "hasn't done anything"
- **Vocalness: 85%** - Begs loudly for his life
- **Obedient: 10%** - Resisting, lying to Ashley
- **Desire: 0%** - No indication of attraction

**Iconic Quote Added:**
> "I haven't done anything!" — Timothy Walker lying to Ashley, Strange Behaviours

**Key Traits:**
- Convicted serial killer, drifter who murdered several hitchhikers
- Sentenced to death only a week before the story
- Death sentence carried out via VortexFoods™ packaging and sale
- Ashley calls out his lie with contempt
- Ashley reads about his "execution" the next day while disposing of his remains on the toilet

---

### 5. **Mary Taylor** (Supporting Character)

**No Percentage Bars** - Not a predator or prey in this story

**Iconic Quote Added:**
> "Shrunken or not, those little beings ar... were human beings like you and me." — Mary Taylor, Strange Behaviours

**Key Traits:**
- Ashley's mother, a physician
- Represents older generation's moral objections to VortexFoods™
- Privately objects on humanitarian grounds
- Believes shrunken people are/were human beings regardless of legal status
- Ashley views her as "misguided" but loves her
- Shows discomfort when Ashley eats shrinkies in front of her

---

### 6. **Robert Taylor** (Supporting Character)

**No Percentage Bars** - Not a predator or prey in this story

**Iconic Quote Added:**
> "They're ramping up patrols down south again..." — Referenced indirectly, Strange Behaviours

**Key Traits:**
- Ashley's father, Coast Guard officer
- Working long hours due to heightened security after narcotics submarine incident
- Pragmatic, not sympathetic to wife's moral reservations about Vortex
- Described as reclusive, prefers tinkering with vintage cars in garage

---

## Percentage Bar System Explanation

### For Predators:
1. **Shrinkie Cravings** (0-100%): Frequency of eating VortexFoods, speed of consumption, how appetizing shrinkies are, enjoyment of taste/squirming
2. **Cruelty** (0-100%): Intentional harm/taunting beyond simple consumption, violation of tiny bodies, cruel taunts, intentional scaring
3. **Playfulness** (0-100%): Playing with tinies before eating (not necessarily cruel), death games, prolonged mouth play, mischievous interaction
4. **Intimate Behavior** (0-100%): Lack of clothing around tinies, using them for pleasure, sexual use
5. **Supports Vortex/Righteousness** (0-100%): Support for business practices, justification that it makes world better, belief they're removing criminals

### For Prey (Shrunken People):
1. **Intelligence** (0-100%): Ability to escape or reason their way out
2. **Fear** (0-100%): How terrified they are
3. **Vocalness** (0-100%): How much they beg or attract predator attention
4. **Obedient** (0-100%): Compliance with predator's wishes
5. **Desire** (0-100%): Intimate feelings toward predator (attraction, sneaking looks at body)

---

## Technical Updates Made

### Files Modified:
1. **data.js** - Added percentage bar values and iconic quotes to all 6 characters from Strange Behaviors
2. **characters.html** - Added rendering functions for percentage bars and iconic quotes

### New Functions Added to characters.html:
- `buildPercentageBar(label, value, color)` - Renders individual percentage bar with label and value
- `buildPercentageBars(c)` - Determines if character is predator or prey and renders appropriate bars
- Updated `buildProfile(c)` - Now includes percentage bars and iconic quote display

### Display Features:
- Percentage bars use color coding:
  - Predator bars: Red (#c0392b)
  - Prey Intelligence: Blue (#3498db)
  - Prey Fear: Red (#e74c3c)
  - Prey Vocalness: Orange (#f39c12)
  - Prey Obedient: Green (#2ecc71)
  - Prey Desire: Purple (#9b59b6)
- Iconic quotes displayed in special formatted box with red left border
- Percentage bars show animated width transitions

---

## Story Context Notes

**Strange Behaviors** is the first story in the American Setting and establishes:
- Ashley Taylor as the primary American predator character
- The casual, normalized consumption of shrinkies in American society
- Generational divide on Vortex ethics (Mary vs Ashley)
- Brian as a unique prey character (vorarephile who desires being eaten)
- Variety of prey types: political threats (Megan), criminals (Timothy), and unusual cases (Brian)

The story is told primarily from Brian's perspective with secondary perspective from Ashley, creating an intimate look at both predator and prey psychology in this universe.

---

## Kill Count Status

As instructed, kill counts were **NOT** modified as they were already updated in the wiki. The current documented kills remain:
- **Ashley Taylor**: 4 named victims + ~47 anonymous = 51 total estimated
- **Brian, Megan Sanders, Timothy Walker**: All deceased, consumed by Ashley Taylor

---

## Next Steps

For future story updates, the same process should be followed:
1. Read the story thoroughly
2. Identify all named characters (predators and prey)
3. Assign percentage bars based on their actions and traits in the story
4. Select iconic quotes that capture each character's essence or pivotal moments
5. Update any other wiki sections affected (lore, factions, stories list)
6. Verify kill counts are accurate but don't modify if already set
