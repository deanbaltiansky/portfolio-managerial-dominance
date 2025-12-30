---
title: "Explaining Managerial Dominance: The Role of Relationship Expectancies"
output:
  html_document:
    self_contained: true
    md_extensions: +raw_html
---

# Problem

Managers sometimes behave **dominantly** toward employees, using threats, coercion, or an aggressive tone in an attempt to exert influence. In many cases, this behavior is not intended to harm relationships. Rather, it reflects an instrumental choice: dominance is used because it is believed to be effective.

Yet dominant behavior can carry **relationship costs**, including reduced trust, liking, and respect. Despite these risks, managers vary widely in their willingness to use dominance. This raises a practical question for organizations: **why do some managers rely on dominant tactics, even when it may lead to strenuous relationships between them and their employees?**

I propose that managers’ **beliefs** about the relational impact of dominance matter. Many managers who behave dominantly do **not** discount relationship outcomes and do **not** intend to cause relational harm. Instead, they operate under a **belief-based blind spot**: they underestimate the extent to which dominance harms relationships, believing it may be effective *without* being especially costly to the relationship.

I distinguish between three potential drivers of dominant behavior:

  1. **Influence expectancies**: beliefs about whether dominance will increase *compliance*.
  2. **Relationship motivations**: the extent to which managers *care* about their relationships with employees.
  3. **Relationship expectancies**: beliefs about the *relationship impact* of dominant behavior.

These situation-specific beliefs do not operate in a vacuum. I trace relationship expectancies back to a broader social mental model: **competitive worldview**—the belief that the social world is a constant battle for status and resources. Managers with a competitive worldview are more likely to view dominance as **normal, acceptable, and unobjectionable**, and therefore to expect limited relationship harm. In turn, these expectations increase the likelihood that they will behave dominantly.

# Executive summary

# Evidence strategy

**Finding the unique roles of relationship expectancies and competitive worldview in predicting dominance**

The first challenge is separating beliefs about the **relationship impact of dominance**, and the broader **competitive worldview**, from alternative predictors of dominant behavior. In **Study 1**, I use well-established measures and multilevel modeling to test whether relationship expectancies drive dominant strategies at work, whether competitive worldview informs these beliefs, and whether these effects hold above and beyond influence expectancies, relationship motivations, and related mental models.

**Grounding the model in real workplace experiences**

A second challenge is whether these patterns hold beyond abstract self-report measures. In **Study 2**, I ground dominance in real workplace experience by collecting employee descriptions of actual managerial dominance and examining how others forecast its relationship impact and their own willingness to behave dominantly in the same situations.

**Observing dominant behavior under incentives**

A third challenge is whether stated intentions reflect how managers behave when real outcomes are at stake. In **Study 3**, I observe dominant behavior directly using an incentive-compatible manager–employee role-play, allowing me to test whether relationship expectancies predict actual dominance (even at the potential cost of financial loss) and whether dominant managers *underestimate* relationship harm or non-dominant managers *overestimate* it.

**Establishing a causal effect**

Finally, correlational evidence cannot fully establish whether relationship expectancies *lead to* dominant behavior. I address this in a separate experiment that directly manipulates relationship expectancies and measures subsequent dominance choices, described in a companion A/B testing report (see LINK).

# Study 1: The unique roles of relationship expectancies and competitive worldview

<div style="margin-top: 0;">
  <p style="margin:0 0 12px 0;">
    <a href="https://deanbaltiansky.com/dominance-in-the-competitive-jungle/studies/study-1/index.html" target="_blank" rel="noopener"
       style="background:#0b69ff;color:white;padding:0.55em 0.9em;border-radius:8px;text-decoration:none;display:inline-block;margin:0;">
      FULL REPORT ↗
    </a>
  </p>
</div>

## Procedure

To test whether competitive worldview uniquely predicts relationship expectancies and dominance strategies over and above alternative explanations, and whether relationship expectancies uniquely drive this effect over and above alternative mediators, I conducted a study of 275 full- and part-time employees. 

The primary measures of interest were:

  - **Competitive worldview** (agreement with 10 statements; Cronbach's $alpha$ = .83; e.g., *it's a dog-eat-dog world where you have to be ruthless at times*)
  - **Dominance strategies** at work (extent to which nine behaviors and strategies desrcibe the participant at work; Cronbach's $alpha$ = .86; e.g., *I am willing to use aggressive tactics to get my way at work*)
  - **Relationship** and **influence** expectancies of dominance: For each of the none behaviors and strategies from the dominance scale, participants indicated the impact they believe it has on relationships with others (1 = *Strong negative effect on relationships* to 7 = *Strong positive effect on relationships*; Cronbach's $alpha$ = .85) and influence over others (1 = *Strong negative effect on influence* to 7 = *Strong negative effect on influence*; Cronbach's $alpha$ = .86)

As control variables and other alternative explanations, I measured **status zero-sum beliefs** (e.g., *when status for one person is increasing it means that status for another person is decreasing*), **cooperative primal beliefs** (e.g., *the world runs on trust and cooperation way more than suspicion and competition*), coercive theories of power** (e.g., *people mainly gain power by force” and “An influential individual is typically intimidating*), **collaborative theories of power** (e.g., *people rise in power through virtue and respect” and “Influential individuals need to be approachable and empathetic*), **relationship motivations at work** (e.g., *in your work life, to what extent do you care about having good relationships with the people you work with?*), **prestige strategies at work and their relationship and influence expectancies** (e.g., *my peers at work respect and admire me* ), gender, race, income, education, and age.

## Correlations

I examine descriptive-level correlations between the variables. Notably, competitive worldview is strongly and positively correlated with dominance strategies (*r* = .54) and relationship expectancies of dominance (*r* = .51). Additionally, relationship expectancies of dominance are positively correlated with dominance strategies (*r* = .62).

<img src="assets/correlationplot.png" style="width:70%; height:auto;">

<div style="margin-top: 0;">
  <p style="margin:0 0 12px 0;">
    <a href="https://deanbaltiansky.com/dominance-in-the-competitive-jungle/studies/study-1/app/index.html" target="_blank" rel="noopener"
       style="background:#0b69ff;color:white;padding:0.55em 0.9em;border-radius:8px;text-decoration:none;display:inline-block;margin:0;">
      INTERACTIVE CORRELATIONS EXPLORER ↗
    </a>
  </p>
</div>

## Discriminant validity

To disentangle the unique variance predicted by competitive worldview and explained by relationship expectancies of dominance, I conducted a 10,000-bootstrapped simultaneous mediation model. In that model, I controlled for status zero-sum beliefs, cooperative primal beliefs, relationship motivations, coercive theories of power, collaborative theories of power, age, race, income, gender, and education. 

First, the total effect of competitive worldview on dominance strategies at work shows that, controlling for alternative explanations, those with a competitive worldview tend to prioritize dominance in an effort to exert leadership in the workplace (*b* = .75, *t*(254) = 8.85, 95% CI = [0.58, 0.91], *p* < .001). 

Second, the effect of competitive worldview on relationship expectancies of dominance shows that, controlling for alternative explanations, those with a competitive worldview believe that dominance will incur lower relationship harm (*b* = .60, *t*(254) = 8.85, 95% CI = [0.47, 0.73], *p* < .001).

<div style="margin-top: 0;">
  <p style="margin:0 0 12px 0;">
    <a href="https://deanbaltiansky.com/dominance-in-the-competitive-jungle/studies/study-1/lm-table-app/index.html" target="_blank" rel="noopener"
       style="background:#0b69ff;color:white;padding:0.55em 0.9em;border-radius:8px;text-decoration:none;display:inline-block;margin:0;">
      EXPLORE LINEAR MODELS ↗
    </a>
  </p>
</div>

Third, to test my core claim, I inserted both *relationship* expectancies dominance and *influence* expectancies of dominance as simultaneous mediators, controlling for one another. Indeed, the indirect effect of relationship expectancies of dominance explained 41.1% of the total effect, whereas the indirect effect of influence expectancies of dominance explained only 4.8% of the total effect.

<img src="assets/s1-mediation.png" style="width:100%; height:auto;">

<div style="margin-top: 0;">
  <p style="margin:0 0 12px 0;">
    <a href="https://deanbaltiansky.com/dominance-in-the-competitive-jungle/studies/study-1/mediation-app/index.html" target="_blank" rel="noopener"
       style="background:#0b69ff;color:white;padding:0.55em 0.9em;border-radius:8px;text-decoration:none;display:inline-block;margin:0;">
      TEST OTHER MEDIATION MODELS ↗
    </a>
  </p>
</div>

Overall, this suggests that: (1) competitive worldview uniquely predicts relationship expectancies of dominance and dominance strategies, over and above alternative mental models; and (2) relationship expectancies of dominance, rather than influence expectancies of dominance or relationship motivations, are driving the effect of competitive worldview on dominance strategies. 

# Study 2: Qualitative descriptions of managerial dominance

<div style="margin-top: 0;">
  <p style="margin:0 0 12px 0;">
    <a href="https://deanbaltiansky.com/dominance-in-the-competitive-jungle/studies/study-2/index.html" target="_blank" rel="noopener"
       style="background:#0b69ff;color:white;padding:0.55em 0.9em;border-radius:8px;text-decoration:none;display:inline-block;margin:0;">
      FULL REPORT ↗
    </a>
  </p>
</div>

## Descriptions of dominance

To test the hypothesized model in ways that resemble employees' lived experiences much more closely, I went straight to the source. I asked full- and part-time employees to describe a time in which they manager behaved dominantly in an effort to exert influence. These qualitative descriptions added depth and color to the precision demonstrated in Study 1. Below are the 23 anonymous descriptions that employees wrote about their managers (shared with full consent):

<div style="max-height:400px; overflow-y:auto; border:1px solid #ddd; padding:8px;">

<table style="width:100%; border-collapse:collapse;">
  <thead>
    <tr>
      <th style="text-align:left; border-bottom:1px solid #ddd; padding:6px;">
        Description
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I work as an Ecommerce Specialist for a Fabric company that is expanding their virtual presence. As such, I make many nuance and minor decisions about the visual layout as well as the descriptions and images used for items/listings. All of these add up to a much bigger picture to increase sales and revenue. My manager was trying to get me to use hand-made and uploaded images for each listing, versus finding the manufacturing made or other second hand made images. This would be far more time consuming and would hurt our ability to streamline. The manager basically demanded that I did so, and told me that it was an order, and that they will hire someone to produce those images and provide them too me. They weren't too loud, but they were forceful.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I was up for a promotion at work, and for context should add I was also 34 weeks pregnant. We were working to debut a product our engineering team had been working on. My manager was trying to get me to fly cross country to present our product to the board. They didn't ask if I wanted to go, and they knew I wasn't allowed to fly because of my pregnancy and said if I involved HR I would be sorry.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I work at a school, and I work with my supervisor in the Spring to coordinate testing. Well, my elderly Mom had a doctors appointment for one of those days, and I asked for it off to be with her, thinking that she would be ok on her own for one day. She flew into a rage and yelled at me so much that spit got on my face. She intimidated me into not taking that day off and to reschedule Mom's appointment.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I am a worker at a retirement home and for some reason there is a chair in a person's bathroom which I sit sometimes to take a short break. My boss saw me one time, marched me to her office and had a chat with me, telling me I can't do that. I said very little and got out of there as soon as I could.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I work as a librarian, my manager wanted me to spearhead a project for a new children's exhibit. I was very busy working on other projects for another manager and told her this. I found out they were the ones put in charge of the exhibit and were trying to foist it onto me. She threatened to revoke my already established days off.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I am a lab manager for a forensics lab. My manager wanted me to have the lab accredited through a national accreditation agency. He ordered me to do an enormous amount of documentation, research, and other work knowing I wouldn't be compensated for the additional work, and he told me he simply didn't care how many extra hours I had to put into it. He was stern and rude about it.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I worked at a small business gift shop owned by a local man. One winter, he was annoyed that sales were low. He told me unless I started to sell more, he wouldn't reimburse me for my Uber rides home anymore. He thought by threatening me, I would become a better salesperson.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I worked at Bath and Body Works. Our manager at the time wanted us to give everyone that walked in a hand massage with the lotion. I don't like touching random people so I wasn't doing it. She pulled me to the back and sternly let me know she wasn't happy with me not doing it.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        My manager was trying to get me to file paperwork at a court that I knew was not correct. He was very insecure with himself and his role as manager and wanted to show me that he was boss and I had to do what he wanted. Even though I was just a paralegal, I knew the correct information that needed to be included in the court document before it was filed with the court. I brought this point up to my manager and he basically told me I didn't know what I was talking about and that I just needed to do as he asked. He called me into his office and told me sternly my job was to do his work as he requested. I was very hesitant and didn't know what to do because I knew if I filed the paperwork as is, it would be rejected by the court.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I work in accounting and my supervisor oversees just our sector of accounting, not all of accounting for the whole company. I tend to be more savvy in the accounting software than the rest of my team including my manager. I will find more efficient ways to complete reports or tasks. I will share these findings in my group's Teams chat. My boss will often speak down to me or try and pinhole my solutions on Teams. She speaks to me like a child and will say things like "did I tell you to find a new way to do this or did I ask you to run the report as we always do?" or "Is there a reason you did xyz when the rest of us are ok with doing abc like I ask?"
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        It was a project which was awarded to my manager, he couldn't keep up with the project and then asked for my help in the project completion. While in the process of the getting the project done, my method of getting the work done was different from his and it was getting noticeable. He began asserting dominance stating the project was his and things needs to be done his way and I was only trying to be on the spotlight by using my method.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I was working as a cashier at a grocery store. I was tasked with asking customers to donate to a children’s charity. That day, many customers declined to donate. The manager, who was responsible for running the store, called me to the back room and immediately accused me of not doing my job. He used a tone that was accusatory and bossy, stating that I was not asking for donations. He wanted me to obtain more donations so the store could beat others in the competition to raise the most funds.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        My current manager told me, when I was first hired, that I completed my cleaning of the rooms too slow. She wanted me to go faster, so she reminded me that there were many people that were faster than me and if I kept performing the way I was performing she would let me go.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I was working at a commerical bank a couple of years ago, and my acting director, who was my de facto line manager, became very unappy when he found out that I was responding to the CFO regarding an issue that the CFO had emailed me directly about. This led to a very heated argument where he accused me of not respecting hierarchy and authority, and he began yelling and shouting and throwing things around.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        My manager was determined to revamp our company's social media strategy to increase sales, engagement and brand visibility. Her dominant behavior manifested in various ways throughout the process. First, she held a high-pressure meeting where she outlined her vision with unwavering confidence, leaving little room for dissent. Her tone was authoritative, and her body language exuded a sense of control, effectively conveying her expectations to the team.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        There was a job that needed to be attempted the way that the company wanted it to be accomplished by following a set of instructions that were left by the client. The supervisor made sure we worked on teams and watched everyone including myself like an owl because he wanted it done as instructed. The supervisor was very demanding with the job and at times made it unbearable to do our job.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        Several years back I was working at a gym. There's usually 3-4 of us at the front desk answering calls, signing people up for membership, giving tours, and answering general questions/concerns people may have. There's also generally one person designated to janitorial duty/cleaning at all times. The janitor duty wasn't mine, but occasionally we did help with cleaning tasks. On this day, no different than any other day, I was briefly chatting with a friend at the gym in sight of the front desk. My manger at the time realised this and yelled at me to go clean something. I put an emphasis on yelled because it was definitely not common and primarily due to that fact was talking to a friend. I said okay and continued talking to close the convo. After about a min. or two, he yelled again. So this time, I immediately closed the convo with my friend, kind of looking at each other with a slight grin realising the power trip going on.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I work as a nurse in a healthcare facility taking care of patient needs is my role.my manager is my nurse in charge and oversees my roles and allocates duties if necessary.He one day asked me to take up my colleague's duties as i was signing out. he did it forcefully without considering my plans and state of fatigue.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        My role is working in disease control for state government and my boss is the program manager. We work in tuberculosis control and treat patients and try to keep the disease from spreading. She also sees patients but works more administratively usually and as a point of contact. I had recently come back from vacation and a few weeks later, my boss said my focus at work seems off in general and wrote a list with a few examples of things she had seen. She told me she is not a micromanager but can be toward me if needed and that if I can't find something to do, she can always find plenty, that my work quality reflects on her and that I'm not to make her look bad.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I worked as a Program Manager for a large customer. My manager was a Director at our company. He invited himself to a customer meeting that had been scheduled in another city. He wanted to review the customer and our operations. My team met him at a hotel before meeting with the customer. The customer environment was business casual, so my team dressed for that. In fact, business casual dress was common for all customer engagements. My manager did not approve. He strongly demanded that the entire team wear formal suits, ties and/or dresses for any and all customer visits. He was verbally abusive about the situation. Next, he noticed that some of the hotel rooms we were staying in during the customer visit were more expensive than others. He demanded that only senior-level employees be allowed to stay in the more expensive rooms, and actually made us change our reservations.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I had a manager that was very dominant when I worked in a warehouse. We would take frozen prepared food and load pallets and trucks. He would constantly threaten to let us go if we did not do things fast enough for his liking and would constantly use fear of our job security to get his way right away. One day at work I had the flu and working the freezer and he was constantly badgering me for being so slow that day. I tried to use a sick day but he refused to let me take sick time saying he we was short staffed. So I was really sick working in a freezer and getting constantly badered by this manager.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I work as a delivery driver and one of my responsibility is to see that the vehicle is washed in the evening of the day or after the day's work. There are few days that I couldn't take the vehicle to the washing station due to lateness and time factor. This lateness is mainly caused by people in the itinerary department or sometimes delay from customers. Whenever my boss sees the condition of the vehicle the following morning, he verbally attacks me and threatens me with letter of queries. He would insist that I get the vehicle washed myself on the spot. He would always try to absolve the guys in the itinerary of any blame and put all blames on me. He would always insist that the vehicle must always be in pristine condition irrespective of any lateness or lapses from other people.
      </td>
    </tr>
    <tr>
      <td style="padding:6px 6px 12px 6px;">
        I work as a software test engineer and my manager was trying to make me sign off on the latest module we implemented. There was a lot of pieces to test and I was not given enough time, because the development team did not finish on time. My manager was contacting me multiple times every day if I was finished. He would just repeat the same sentences, he said we really needed to finish the tests and hand it over, otherwise it would be a huge problem with the release.
      </td>
    </tr>
  </tbody>
</table>

</div>

## Reactions to descriptions

After collecting these descriptions, I proceeded to the primary sample: 289 participants were shown one randomly-selected description and were asked to react to it. Specifically, estimated the effect that the manager's behavior had on their relationship with the employee (*Extremely Negative* to *Extremely Positive*), the impact it had on the employee's compliance with the task (*Not at All* to *Completely*), and whether they would behave as the manager did if they were in that situation (*Not at All Likely* to *Extremely Likely*). Reactions to the descriptions, accompanied by a measure of participants' competitive worldview, offered an important element of external validity to the project's core claim.

For the primary analyses, I conducted a set of random effects models, holding description as a random effect to examine the variance within each description rather than between descriptions. This is because the descriptions varied quite a bit from one another and I wanted to hold them constant. The first random effects linear model showed that competitive worldview was a significant and positive predictor of behaving dominantly, like the manager, in that situation ($\hat{\beta}$ = 0.18, 95% CI = [0.05, 0.31], *p* = .008). The second random effects linear model showed that those with a competitive worldview were also more likely to estimate a positive impact of the manager's behavior on their relationship with the employee ($\hat{\beta}$ = 0.32, 95% CI = [0.18, 0.45], *p* < .001). 

Crucially, relationship expectancies performed much better as a mediator than influence expectancies. I conducted a 10,000-bootstrapped structural equation model, clustered within scenario, with both relationship and compliance expectancies as simultaneous mediators. Remarkably, the indirect effect of relationship expectancies explained 81.6% of the total effect ($\hat{\beta}$ = 0.11, 95% CI = [0.05, 0.17], *p* = .001), whereas the indirect effect of compliance expectancies did not explain a meaningful portion of the total effect ($\hat{\beta}$ = -0.01, 95% CI = [-0.03, 0.02], *p* = .579).

# Study 3: Incentive-compatible behavioral experiment

<div style="margin-top: 0;">
  <p style="margin:0 0 12px 0;">
    <a href="https://deanbaltiansky.com/dominance-in-the-competitive-jungle/studies/study-3a/index.html" target="_blank" rel="noopener"
       style="background:#0b69ff;color:white;padding:0.55em 0.9em;border-radius:8px;text-decoration:none;display:inline-block;margin:0;">
      FULL REPORT ↗
    </a>
  </p>
</div>

## Experimental design

## Behavioral effects

## Comparison to ground truth

## Crowd-sourced dominance

<div style="margin-top: 0;">
  <p style="margin:0 0 12px 0;">
    <a href="https://deanbaltiansky.com/dominance-in-the-competitive-jungle/studies/study-3b/index.html" target="_blank" rel="noopener"
       style="background:#0b69ff;color:white;padding:0.55em 0.9em;border-radius:8px;text-decoration:none;display:inline-block;margin:0;">
      FULL REPORT ↗
    </a>
  </p>
</div>

# Study 4: Causal Impact of Relationship Expectancies

<div style="margin-top: 0;">
  <p style="margin:0 0 12px 0;">
    <a href="https://deanbaltiansky.com/dominance-in-the-competitive-jungle/studies/study-4/index.html" target="_blank" rel="noopener"
       style="background:#0b69ff;color:white;padding:0.55em 0.9em;border-radius:8px;text-decoration:none;display:inline-block;margin:0;">
      FULL REPORT ↗
    </a>
  </p>
</div>

# Implications for organizations