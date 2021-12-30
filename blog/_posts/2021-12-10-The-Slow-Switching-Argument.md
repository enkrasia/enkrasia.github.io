---
lyout: post
title: The Slow-Switching Argument&#58 A Williamsonian Counterfactual Analysis
category: 哲学
truncated_preview: true
excerpt_separator: <!--more-->
---

<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

In his *The Philosophy of Philosophy*, Timothy Williamson (2007) argues that thought experiment arguments should be formulated in terms of the counterfactual conditional. By analysing Gettier's argument against the justified true belief (JTB) principle of argument, a paradigmatic thought experiment argument in philosophy, he finds that the argument has the following structure (2007, p. 181-187).

<!--more-->

First, The argumnet's target analysis is a claim of necessary and sufficient conditions for knowing (where $J$ stands for 'having a JTB for'):

(1) $\Box \forall x \forall p(K(x, p) \leftrightarrow J(x, p))$

Second, the argument is based on some imaginary story,  We can represent a Gettier-style story by G(X, P), meaning that X bears a Gettier-relation to P, i.e., having a JTB for P on the basis of some justified false belief:

(2) $G(X, P)$

Third, given this imaginary story, it is possible that there is at least one subject and one proposition such that this subject bears a Gettier-relation to this proposition:

(3) $\Diamond \exists x \exists p (G(x, p))$

Four, if there were an instance of one's bearing Gettier-relation to some proposition, then any instance of one's bearing Gettier-relation to some proposition is an instance of one's having a JTB for this proposition without knowing it:

(4) $\exists x \exists p (G(x, p) \Box \rightarrow \forall x \forall p (G(x, p) \rightarrow (J( x, p) \land \neg K(x, p)))$

Five, (3) and (4) logically entail that:

(5) $\Diamond \exists x \exists p (J(x, p) \land \neg K(x, p))$

(5) falsifies (1), namely, the JTB principle of knowledge.

# The Williamsonian Counterfactual Framework
We can then, on the basis of Williamson's analysis of Gettier's argument, formulate a general framework for any Gettier-style thought experiment argument, as follow:

The Target Analysis

(TA) $\Box \forall x (Fx)$

An Imaginary Story

(IS) $DX$

The Possibility Premise

(PP) $\Diamond \exists x(Dx)$

The Counterfactual Premise

(CP) $\exists x(Dx) \Box \rightarrow \forall x(Dx \rightarrow \neg Fx)$

The Conclusion

(CO) $\Diamond \exists x(\neg Fx)$

# The Slow-Switching Thought Experiment Argument
The Slow-Switching (SS) Argument is an argument against the compatibility between content externalism and privileged access. It is based on a modification of Putnam's famous Twin-Earth thought experiment where an agent is unwittingly switched between Earth and Twin-Earth. 

It turns out that the SS argument is structurally parallel to Gettier's argument, for two reasons:
1. The inference of the SS argument is based on the intuition abstracted from an imaginary story, i.e., a slow switching story.
2. The target analysis of the SS argument *can be* a universal, necessary statement, i.e., the principle privileged access.

# Applying the Framework
Based on Boghosian's (1989) version of the SS argument, we can formulate the argument in terms of the counterfactual framework as follow:

(TA-SS) $\Box \forall x \forall p (T(x, p) \rightarrow K(x, T(x, p)))$

(IS-SS) $S(X)$

(PP-SS) $\Diamond \exists x S(x)$

(CP-SS) $\exists s S(x) \Box \rightarrow \forall x \forall p (S(x) \rightarrow (T(s, p) \land \neg K(s, T(s, p)))$

(CO-SS) $\Diamond \exists s \exists p (T(s, p) \land K(s, T(s, p)))$

(CO-SS) can falsify (TA-SS).

# A Modification?
Some may object that, given content externalism, the concept that the subject in question possess on Earth should be different from that on Twin-Earth. Therefore, it is wrong to say that, as (PP-SS) represents, one, who is in the switching situation and thinks (solely) about P, lacks the privileged access to this P-thought.

In response, we can modify (IS) in the way that it can represent the SS situation more presciently, that is, representing a subject who have had both P-thought and its Twin-Earth counterpart. Let us introduce the Twin-Earth operator $t$ such that $tP$ is the Twin-Earth counterpart of $P$. We can then modify the original formulation as follow: 

(IS-SS*) $S(X) \leftrightarrow (T(S, P) \land T(S, tP))$

(PP-SS*) $\Diamond \exists x \exists p (T(s, p) \land T(s, tp))$

(CP-SS*) $\exists s \exists p(T(s, p) \land T(s, tp)) \Box \rightarrow \forall x \forall p ((T(s, p) \land T(s, tp)) \rightarrow (T(s, p) \land \neg K(s, T(s, P)))$

(CP-SS*) can still entail (CO) which falsifies (TA-SS), namely, the principle of privileged access.

# Reference
Boghossian, P. A. (1989). Content and Self-Knowledge. *Philosophical Topics*, 17(1), 5–26.
Williamson, T. (2007). *The philosophy of philosophy*. Blackwell Pub.
