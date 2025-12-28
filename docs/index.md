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

## Discriminant Validity

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

## Descriptions of dominance

## Expected impact

# Study 3: Incentive-compatible behavioral experiment

## Experimental Design

## Behavioral effects

## Comparison to ground truth

## Crowd-sourced dominance

# Implications for organizations