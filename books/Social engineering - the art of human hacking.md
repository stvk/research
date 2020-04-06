# Social Engineering: The Art of Human Hacking (by Christopher Hadnagy)
## Notes

<!-- TOC -->

- [Social Engineering: The Art of Human Hacking (by Christopher Hadnagy)](#social-engineering-the-art-of-human-hacking-by-christopher-hadnagy)
    - [Notes](#notes)
- [Ch 1 INTRODUCTION](#ch-1-introduction)
    - [Pre-conditions for social engineering.](#pre-conditions-for-social-engineering)
- [Ch 2 GATHERING INFORMATION](#ch-2-gathering-information)
    - [Online Information Gathering Considerations](#online-information-gathering-considerations)
        - [Sources](#sources)
    - [Physical Information Gathering](#physical-information-gathering)
        - [Simple observation](#simple-observation)
- [Ch 3 ELICITATION](#ch-3-elicitation)
    - [Elicitation Tips](#elicitation-tips)
    - [Types of questions](#types-of-questions)
- [Ch 4 PRETEXTING](#ch-4-pretexting)
    - [Principles of pretexting](#principles-of-pretexting)
    - [Examples](#examples)
    - [Legalities](#legalities)
    - [Tools](#tools)
- [Ch 5 MIND TRICKS](#ch-5-mind-tricks)
    - [Modes of thinking](#modes-of-thinking)
    - [Microexpressions](#microexpressions)
    - [Neurolinguistic Programming (NLP)](#neurolinguistic-programming-nlp)
    - [Building Instant Rapport](#building-instant-rapport)
    - [Human Buffer Overflow](#human-buffer-overflow)
- [Ch 6 INFLUENCE](#ch-6-influence)
    - [Principles](#principles)
    - [Tactics](#tactics)
    - [Alerting Reality](#alerting-reality)
    - [Manipulation in social engineering](#manipulation-in-social-engineering)
- [Ch 7 THE TOOLS OF THE SOCIAL ENGINEER](#ch-7-the-tools-of-the-social-engineer)
- [Ch 8 CASE STUDIES](#ch-8-case-studies)
- [Ch 9 PREVENTION AND MITIGATION](#ch-9-prevention-and-mitigation)

<!-- /TOC -->

# Ch 1 INTRODUCTION
## Pre-conditions for social engineering.

• Create state of panic
• Using influence, or manipulation tactics
• Create a sense of trust

A social engineer is only as effective as the information they gather. It is "the crux of every social engineering engagement"

Definition: The act of manipulating a person to take an action that may or may not be in the target's best interest.

# Ch 2 GATHERING INFORMATION

## Online Information Gathering Considerations

*   Tools: WYD, Maltego
*   Profile the company as a whole to develop a company profile, pretext, and questions to use/days to call/come onsite etc.
*   Develop a communication model (Shannon & Weaver model): 
    * Information source produces message
    * Transmittor encodes messages into signals
    * Channel signals transmitted
    * Receiver decodes the signal
    * Destination where the message arrives
* 3 levels of problems 
    * Technical problem: accuracy of transmission
    * Semantic Problem: how precise is meaning conveyed
    * _Effectiveness problem:_ how effectivley does the perceived meaning effect the bahviour? -- this is the problem of social engineering; i.e. "how does the message effect behaviour in a way that the social engineer wants?"
* Use a simpler model: Sender, channel, receiver model:
    * Understand your goal; ask the question: what do you want out of the communication?
    * Understand the channel; phishing email? onsite visit? face to face discussion?

### Sources

*   Corporate/personal website
*   Whois information
*   Image search
*   Employee contact info
*   Employee resumes
*   Forums (good for finding about hobbies)
*   anything relevant to the company
*   Google operands - .dat .cfg .pdf. docx etc
*   Social Network sites - twitter blipy pleaserobme icanstalkyou (decommissioned) facebook linkedin myspace
*   Technical sources also useful: 
    *   SMTP, SNMP, DNS etc.
    *   Use Google to find data (i.e. use operands to find .dat .cfg on servers) googleguide.com/advanced_operators.html
    *   Shodan to reveal infrastructure exposed externally

## Physical Information Gathering

### Simple observation 
*   Keys vs rfid cards to enter?
*   smoking areas
*   dumpster locked?
*   external cameras?
*   power supplies/external heating and cooling reveal the service company)

# Ch 3 ELICITATION

* Why it's so effective: Most people want to be helpful, appear well informed/intelligence, talk about their accomplishments, desire to be polite, reciprocate kindness
* Goals: The more information you gather, the more successful the elicitation
* Really about estbalishing instant rapport as quickly as possible 

## Elicitation Tips
* Be natural; appearing uncomfortable will kill a conversation - observe your speech and body lanugage in a test conversation beforehand
* Educate yourself so you know what you are talking about, BUT do not play yourself off as an expert; consider asking a question as researcher or student in the area
* Do not be greedy; give something to elicit the feeling of obligation; the conversation must be a give and take unless the other person wants to dominate it
* Control facial expressions: don't be too intense, or appear uninterested
* Preload targets with information about how you want them to react: start from the end result i.e. you want to get information about a project the target is working on; next, come up with pre-load questions adjacent to the subject of that project
* Appeal to ego: you must have a very important job (these need to appear sincere and should be subtle)
* Give opportunities for correction (i.e. give small amount of incorrect information to get the target to correct you)
* Set the mood or tone - sharing bad news with someone may get them to open up about their current or a similar situation
* Assume knowledge and/or volunteer some information - offer information as if you are already in-the-know or have knowledge in a certain area
* Alcohol magnifies above effectiveness
* Balance the amount of questions; too few = awkward, too many = pressuring

## Types of questions
* Open ended: good for eliciting information; study good reporters that do this; use why? and how? at the end of a statement; start with narrow questions that become broader over time
* Close ended questions: good way to lead a target where you want to go in the conversation
* Leading questions: State facts more explicitly than close ended questions can manipulate peoples' memory of an event
* Assumptive question: assumes target already has knowledge i.e. "Where does Mr Smith live?" means the target should assume you know Mr Smith
* Preloading question: "now think carefully before you answer this question" implies the person must be truthful

# Ch 4 PRETEXTING

* The background story, dress, grooming, attitude of the identity that you will assume
* Requires good research to make people feel comfortable releasing information

## Principles of pretexting
* Practice dialects or expressions
* The more research, the better a pretext will appear
* Elimitate dissonance:
    * Reduce importance of dissonace (difficult to do without doing one of the other two things...)
    * Add more consonant beliefs - this is where research will come in handy; i.e. additional knowledge about the rest of the company
    * Change dissonant beliefs (harder but possible)
* If on the phone: 
    * provide backing tracks i.e. bustling office
    * Spoof caller ID
* Simpler pretexts are more successful
* Don't be afraid of failure - that will only increase pressure
* Listen to and pay attention to your target and react accordingly
* Practice spontenaity with friends and family
* Get target to take an action after you're gone so they have a logical conclusion; i.e. can I call you on Monday to get more information? (don't order them around, better to appear that you're there to help them)

## Examples
* Stanley Mark Rifkin
    * Working for a company under contract to develop a backup system for the Security Pacific National Bank wire room, Rifkin learned of the transfer procedures used, and found that bank agents would frequently write down the daily transfer code. One day in mid-October 1978, he made his way into the transfer room, saw the code, memorized it and walked out. Using social engineering techniques, he then made a few phone calls and had $10.2 million wired to the Irving Trust Company in New York City for the credit of the Wozchod Handels Bank of Zurich in Switzerland, where he'd already set up an account.
    * Having previously set up a diamond transaction, he hired a diamond merchant to pick up 43,200 carats (8.64 kg) in diamonds from the Soviet Trading company, which he had purchased for USD 8.1 million. Rifkin then hired a diamond merchant to buy the diamonds from the Soviet trading company in Switzerland. Rifkin then played the role of diamond courier, picked up the diamonds at the airport, put them in his checked luggage, and returned to Los Angeles. He then asked his former lawyer to negotiate giving the diamonds (then worth more than in Switzerland) to the Bank in exchange for a consulting contract to help solve the security problem he identified by his fraud. 
    * It was his former lawyer (not under client/lawyer privilege) who reported him to the FBI. The FBI didn't have enough evidence to prosecute; so they set up and executed a sting luring him into doing another crime where they did have enough evidence to prosecute. He pled guilty. He was captured shortly after, just before midnight on November 5.

## Legalities
* Requires prior research 
* FDC website has guidelines
* False, fictious, fraudulent documents and statements to ilicit information is generally illegal

## Tools
* Props: uniforms, business cards

# Ch 5 MIND TRICKS
## Modes of thinking
* Understand the mode to understand how to talk to people:
    * Kinasthetic - dominant sense is touch "how does that feel to you?"
    * Visual - dominant sense is sight "how does that look to you?" "can you see what I'm saying"
    * Auditory - dominant sense is sound "how does that sound to you?"
* Listen to keywords to understand the mode

## Microexpressions
* Looking at the face to see the underlying emotion; useful to detect deception and to gauge the target's true emotional response during a conversation
* Can last as short as 1/25 of a second but cannot be controlled by the target
* Requires practice (paulekman.com)
* You can become proficiant at faking microexpressions as well - good actors can do this by remembering a specific scenario and evoking the associated emotion

## Neurolinguistic Programming (NLP)
* NLP provides techniques to model human behavior and to install those behaviors in others.
* Using tone and choosing words to open targets up to an idea
    * e.g. Embed commands into a question - downward inflection at end of 
* PlanetNLP.com

## Building Instant Rapport
* Be aware of how you affect people; manage your presence, words, body language to not be consistent with the situation
* Pay attention to the first few seconds of your interaction
* Let people talk about themselves; keep the conversation off yourself
* Empathy is key - identifying feelings/thoughts of the target; use reflection skills; this might need practice if it's not natural to you
* Be well rounded in your general knowledge
* Study target's interest/hobbies/job
* Be open minded to accept others thoughts on a topic; develop curiosity and be non-judgemental
* *Find ways to meet people's needs* 
* Listen to targets vocal tone/speed/colloquialisms and match it
* Mirror targets' body language (can be partial mirroring to not look suspicious)

## Human Buffer Overflow
* "Fuzzing" the target with data to see how they react, and embedding commands
* pre-supposition: Hold a door for someone, then give them a question so they hold the next door (the internal one you don't have access to!) open for you
* Embedded commands - i.e. "buy now" button on a website
    * Provide stories and quotes; they are interpreted as instructions by the listener
* Use negation to embed commands; can embed commands "i.e. don't DO X too much" also includes DO X; and also act like reverse psychology i.e. "you can't tell me what to do"
* Embedded commands may not always work, but they provide a better platform to conduct social engineering

# Ch 6 INFLUENCE

## Principles

1. Set clear goals: Focus on the targets goals first
1. Build Rapport: Allow others to save face, kill them with kindness, also see Ch. 5, Ask questions and then seek to have the person view a request as their idea (preload questions)
1. Be observant of your surroundings - listen and watch
1. Be flexible - don't do the same thing and expect different results
1. Get in touch with yourself - understand your own emotions; change your approach if your emotions and thoughts prevent you from being persuasive

## Tactics
* Gifts should be no strings attached to trigger recipients' sense of obligation strongly
* Information can be better than a physical gift
* Ask for what you want
* Employ obligation - hold the door for someone, stay silent during conversation to get the other person to talk
* Employ concessions (), scarcity (I want to sell you this but this is my last box...; but it must be real or you need to stick to you guns.) 
* Rely on organisational authority; i.e. I spoke with the CFO and she told me...
* You must like people for them to like you in return; project what you want others to feel; but use positive reinforcement backed up by a question to force the target to respond to you

## Alerting Reality
* Framing: People build a series of mental filters through biological and cultural influences and use those filters to understand the world.
    * Framing in social engineering can alert people's perection about reality: i.e. supermarkets use 75% lean labels rather than 25% fat
    * Paint a picture with words to move a target's mind to a new frame.
* Frame bridging: link two ideologically congurent topics:
    * Understand the frame of the target. How does the target want to be perceived?
* Frame amplification: Amplify the focus and beliefs of the taret: e.g. full body xray scanners linked to anti-terrorism was the catalyst to increase xray scanner sales after they were initially poorly received
* Frame transformation: social engineer must create new values/beliefs in the target; most complicated - can take time and effort

## Manipulation in social engineering
* Creation of anxiety or stress 
* Increase target suggestibility (NLP)
* Knowing the targets likes, dislikes, family names etc can allow you to control the target's environment 
* Control your own mental outlook to drive the outcome you desire

# Ch 7 THE TOOLS OF THE SOCIAL ENGINEER

* Caller ID Spoofing to support a pretext (i.e. spoofcard.com, asterix VOIP server)
* Develop speech scripts (practice until it becomes fluent and natural), voice altering software tool
* Password profilers; (John the Ripper, Cain etc) can assist in expediting a password crack; compile from:
    * Social media sites
    * Forums etc.
    * Parts of their name, pet/partners' name
    * Birthday
    * Nickname
    * Address

# Ch 8 CASE STUDIES
...

# Ch 9 PREVENTION AND MITIGATION

* Learn to identify social engineering attacks - employee training
* Create personal security awareness culture
* Identify and understand the data that would be useful to an attacker
* Keep software updated
* Develop scripts for employees that can defend against social engineering requests
* Conduct social engineering audits and implement the recommendations and learnings