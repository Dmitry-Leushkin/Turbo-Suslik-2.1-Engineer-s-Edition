# Backlashes, a.k.a. “Pendulums”

[Book contents](../README.md) | [Part contents](README.md)

1. What pendulums Are and Why They Happen

We'll use the term **pendulum** for the side effects of psychological restructuring - in IT we use the term **“rollbacks”** for a system reverting toward a previous stable state after a deploy. Most often it shows up as sharply negative states: sudden anger, irritation, apathy, fatigue, low mood, disbelief, a sense of hopelessness. Physical symptoms are also common - noticeable loss of strength, zero energy, flare-ups of somatic symptoms, digestive issues, general physical discomfort.

Sometimes it looks like the person just shut down: lying there with no energy, no drive, no sense that any of this is going anywhere. First time you hit this, it's genuinely unsettling - which is exactly why you need the mechanism, not just the symptom, before drawing conclusions.

The term "pendulum" entered use in 2006, early in the work with automated processing routines. The phenomenon itself, though, is old news to anyone who's shipped deep psychological change under any methodology. Fast, significant change in perception, belief, and habitual reaction almost never converges in a straight line. This isn't unique to the psyche - it's how iterative optimization generally behaves: **non-monotonic convergence**. The loss function doesn't drop cleanly on every step. After a real forward shift, there's frequently a short-term move backward - old automatic reactions and legacy interpretations get exercised again, transiently, before the new configuration actually settles.

At this stage plenty of people are genuinely confused: expected to feel better, subjectively feel worse. These temporary regressions are a common reason people abort the work entirely. The typical mistake is treating the surfaced state as foreign - as if the technique or practitioner injected it. In reality, what's surfacing is the user's own pre-existing material - legacy code that was already there, just unreachable until the refactor exposed the path. Most of our own mental activity runs below the observable log level even though it's provably running the whole time - detectable through instrumentation even when it never once printed to console.

Physical symptoms accompanying big shifts are entirely normal - same as the resource spike a lot of people get before exams, travel, public speaking, high-stakes decisions: general system load under stress, not something exclusive to this kind of work. pendulums run on the same principle - difference being, the load here comes from an internal restructuring job, not an external event.

Simple way to frame it: you can't compress something and get output that wasn't already in memory. Squeeze it, and what comes out is exactly what was already allocated. Same with a person: over a lifetime the psyche accumulates a large volume of inefficient automatic reactions, beliefs, defensive routines. As long as they're wrapped in habitual avoidance and distraction - a caching layer sitting in front of them - they barely register. The moment real work strips off the top layer of that caching, the next layer of raw material surfaces: stuff that was always there, just never hit a cache miss before.

Effective work temporarily disables the exception-suppression layer - the habitual masks and defensive wrappers. Result: reactions and impulses that are normally caught and silently swallowed start throwing visibly - irritation, aggression, intolerance, rigid judgment calls. Doesn't mean the person "got worse." Means the automatic reactions stopped being fully hidden from the log. Why isn't there stable acceptance and internal stability already in place, if the corresponding skill was never actually built and tested? Separate discussion. What matters practically here: what do you do with material that just became visible.

To be explicit: this is a model - a working interpretation, not a claim to be the one complete explanation. Other interpretations of side-effect mechanisms exist and hold up fine on their own terms. Deep-diving the root cause of *why* pendulum exists isn't the goal here. The goal is practical: do the work, reduce the internal backlog, keep moving - not get stuck arguing theory.

2. How to Handle pendulums Properly

A few key points up front - makes everything downstream much easier.

**First**, the "junk" surfacing as intrusive thoughts, emotional spikes, and automatic reactions isn't neutral background noise. It's the actual payload generating most of your subjective problems. It usually runs outside direct awareness and gets treated as self-evident, as "just how things are." Working with material that isn't directly conscious gets its own detailed coverage later in the book. What matters right here: **don't identify with this junk.** It's not your core binary. It's not your kernel. It's a badly configured module that got installed at some point through faulty inheritance, not a fundamental property of who you are.

**Second**, you can't fight this material. Trying to go to war with your own running process is a losing setup by construction - no winners in that config. The only workable position is acknowledging current state: logging "yes, this is present right now," without immediately trying to kill it, suppress it, or force it out. Acceptance here doesn't mean agreement or approval - it means refusing to declare war. From there, you can process the surfaced material calmly, in a normal working mode, and watch its influence taper off over successive runs - pendulum frequency and amplitude both trending down.

Can pendulum be avoided entirely? No definitive answer. Backlash effects show up in essentially every methodology that does fast, deep change. I ran into the same pattern back when I was working with neurohacking and direct brain-stimulation methods - TMS documentation explicitly references "snapback" effects: temporary reversion to a prior state. Standard recommendation there: reduce session frequency and intensity. Alex Ramonsky's book *I've Changed My Mind*, covering neurohacking at the physiological/pharmacological level, states plainly that fast change is almost always accompanied by pendulum periods - a felt sense that nothing worked, that the change was illusory, plus heavy emotional states. Any experienced therapist will tell you the same: deep pattern work rarely proceeds without temporary deterioration, including physically. Generalize far enough and pendulum shows up anywhere speed and effectiveness intersect.

Intensity and frequency scale with concurrency: run a low-concurrency queue - one or two jobs a day - and you can go through this whole system with almost no visible backlash. Some people are sensitive even at that load; individual variance here is significant. I personally ran an aggressive mode a lot - many concurrent jobs at once - and got a correspondingly bigger regression the next day. Difference was: I understood the mechanism and had already accepted the likely fallout as temporary. That kept it from turning into a crisis or a reason to stop the pipeline.

Pendulum is not proof "the method doesn't work." It's an indicator the system is actually hitting stable, load-bearing structures - a refactor that never touches live code produces zero regressions. If it's concerning, slow the rate down. Or honestly conclude this working mode doesn't suit you right now. That's also a legitimate call.

3. Types of pendulum and How They Show Up

There's a specific subtype: **pendulum-with-disbelief.** Feels like nothing changed at all, that every problem reverted to its original state, and that everything you've done so far was self-deception. Subjectively very convincing, comes bundled with strong doubt. Its actual function is to stop the pipeline. Any stable change disturbs the system's prior equilibrium, and the system near-reflexively tries to restore its last known-good checkpoint. From the inside this can present as a sudden burst of "objective clarity" - a few days later it usually turns out that clarity was generated entirely from within a temporary state.

Typical states that show up during pendulum - the repertoire is limited and repeats in variations:

- conviction of your own hopelessness, a sense that there's too much internal backlog and it will never clear;
- the thought that the system or technique flatly doesn't work, that the time was wasted;
- pronounced apathy, loss of meaning, a heavy depressive state that can run for several days;
- a sense that every previously processed problem has fully reverted;
- an urge to immediately switch methods, go looking for "something that actually works";
- strong irritation, anger, general emotional tension;
- a conviction that automatic reactions can't be changed at all, in principle;
- physical discomfort, flare-ups of old symptoms, a general sense of falling apart.

Other variants are usually combinations of the above. While you're inside a pendulum, it's very easy to treat its content as ground truth and act on it impulsively. I've made that mistake myself more than once. Track record shows: don't dramatize it, keep the job running, and it clears.

Pronounced pendulums also tend to show up right before a real, visible shift in perception or behavior. The bigger the temporary regression, the more substantial the following change often is - provided you don't kill the process at that exact point. Not a promise or a guarantee - an observed pattern, seen repeatedly across practitioners, not a hard rule.

Stopping the work does often make the pendulum fade over time. Important nuance, though: you can get stuck in an intermediate state where a large chunk of old automatic patterns has already been torn down but no new stable configuration has finished forming yet. Subjectively that reads as prolonged instability, sluggishness, general discomfort. Which is exactly why my own experience says: don't stop the run until you reach a reasonably stable state of emotional and cognitive neutrality - what I informally call **Great Indifference.** Think of it as the system finally reaching steady state, no more oscillation between competing configs.

People who stop mid-run fall into another trap: instead of continuing the actual work, they shift into endless comparative research - chasing "more effective techniques," blaming the current approach for "not working" or "making things worse." Often, at that exact point, the person is one or two months from a genuinely different state - and stops right there. Common pattern. Not a tragedy, not a mistake - just a choice, and each person owns the consequences of it.

There's also a category - call it **constructive pendulum.** A problem surfaces sharply and clearly, essentially throwing directly into awareness with a full, unswallowed stack trace instead of getting caught somewhere upstream. Genuinely unpleasant in the moment, but it hands you a rare, high-signal opportunity: the material surfaces almost unfiltered. All that's required at that moment is to observe and log it. Early on, awareness is often insufficient and the person just reacts - blaming the environment or circumstances. Once the state settles, though, root causes usually either become obvious or get considerably easier to trace and process.

Zoom out and most people are in some version of these pendulum states almost constantly. Difference is: for most, they're suppressed and smoothed over. Look around - chronic irritation, background anger, low-grade latent aggression have become close to baseline. Suppression doesn't eliminate the material, it just defers it. Eventually the accumulated pressure discharges as automatic outbursts - family conflict, sudden arguments, disproportionate reactions to trivial triggers. Since most people never got visibility into their own mechanisms, the actual root cause of these blowups stays undiagnosed. Then the cycle repeats. Inside actual practice, though, a sharp pendulum usually becomes a genuine observation point and processing opportunity - a kind of gift that hands you access to long-buried material.

4. The Dynamics of pendulum Over Time

With active, regular work - say, an average of two automated jobs a day, plus one or two current issues in active processing - the first two to three months can feel like a continuous stream of pendulum. It can genuinely feel infinite, like the backlog has no bottom. This period is usually experienced subjectively as a run of heavy states with only occasional windows of relief and clarity.

After roughly two to three months, intensity usually starts declining, pauses start appearing, balance gets easier to hold. This is often exactly the window where deeper, more foundational patterns start surfacing. Later, pendulum frequency and intensity both drop further, though the system can still "shake" now and then. Normal. Not a malfunction.

Separate mention for pendulum that shows up at the level of external events - sometimes it feels like circumstances themselves start falling apart: a run of setbacks, disruptions, conflicts, almost like the failure is cascading downstream into every dependent system in your life. Doesn't happen to everyone, doesn't happen every time. Resist the pull toward fatalism here - instead, carefully check which beliefs, fears, contradictory expectations, and standing decisions might have shaped that particular configuration of events.

Usually you'll find a set of internal constraints and conflicts driving the corresponding external response. Complaining and self-blame don't do anything useful here. If a situation got shaped by a specific pattern of thinking and reacting, it makes sense to examine it at that same layer. Owning what's happening is a non-optional part of maturity - no way around it.

5. Practical Principles for Getting Through pendulum

To make pendulum easier to run through - assuming, as this book does, that you're aiming for real, relatively fast change rather than years of symbolic effort, so lock in a few working principles ahead of time.

**1. You run on highly selective attention.** The conscious mind - the Frontend - stops flagging problems fast once they stop causing pain. Picture it: something used to keep you up at night, looping constantly, generating strong reactions. Then it gets processed and stops firing. A while later, the typical read is: "eh, nothing much really changed." Meanwhile the fact that something dominating your runtime a week ago has fully cleared just doesn't register - your dashboard only shows open incidents, not resolved ones. Automatic patterns can then convincingly "prove" that nothing happened and the whole effort was pointless. That's why I recommend keeping a running log of states and processed material. Rereading entries from a month or two back usually resolves the "is this even working" question fast.

**2. Memorize a base rule.** Feel bad → pendulum. Feels like nothing got processed → pendulum. Everything feels hopeless → pendulum. Feels like there's too much material and it's unfixable → also pendulum. Not insight, not an "objective read of reality" - a normal nervous-system response, mostly built from learned automatic patterns currently mid-reorganization. Post this rule somewhere visible, literally, so you don't lose track of what you're actually looking at. Even knowing all this, people - myself included - periodically mistake a pendulum for truth and are surprised, a couple of days later, at how seriously they took a temporary state.

A solid tell for pendulum: an abundance of totalizing generalizations. If words like "everything," "never," "always," "nothing" start dominating your internal monologue - "everything's bad," "nothing changed," "this will never end" - you're almost certainly in one.

**3.** **P****endulum gets processed, every time, no exceptions.** First step: acknowledge current state without trying to immediately change it. Simple acceptance formulas work here, same family used across various psychological approaches that emphasize recognition over combat. Once even minimal acceptance is in place, write down every thought and sensation tied to the state and process them one at a time with the tools this book already covers. There are also dedicated automated protocols specifically scoped to pendulum processing - they don't always land instantly, but overall they smooth the process out. Related supporting approaches are covered in the accompanying material.

Understanding pendulum's conditional, constructed nature helps a lot. When a state hits, ask: who exactly is suffering right now? Not accepting the automatic default answer "I" - instead trying to actually identify the specific part, the specific mechanism generating this. Sometimes that single act of inspection is enough to sharply weaken the state, sometimes to the point the drama just dissolves, because no single "sufferer" process can actually be located.

Don't ignore the hardware layer either. Working the psyche loads the nervous system and body directly. Regular physical activity, adequate hydration, basic hygiene after intense sessions all reduce overall load. Reasonable nutrition and supplementation can help - without turning it into fanaticism or a separate cult. The point is simple: don't neglect the hardware while you're only running workloads against the software.

Responsibility for the process sits with you. pendulum can genuinely get intense and subjectively heavy - true, I still remember some of mine with a wince. If you know you're not ready to face states like that, it's fine to say so honestly and not continue. Nobody's forcing this on you. But choosing to run these processes means accepting the possible fallout as part of the deal. Not a call for constant suffering - a willingness to tolerate temporary destabilization if and when it shows up. That's the cost of the result.

And once more: content generated during pendulum can't be trusted. Nothing surfacing in that state is a reliable basis for conclusions about you, the world, or whether the work is effective. It's a temporary re-activation of old patterns - output from a process still mid-transaction. Wait for the state to pass and a more stable read to return before drawing any conclusions.

6. What to Expect Overall

First: pendulum doesn't hit everyone, and not always at severe intensity. Some people run active work and encounter little to no visible backlash. Exact cause of the variance is unclear, though emotional-regulation profile and cognitive-load type likely play a role.

Second: with systematic work, overall internal noise trends down, things get easier to breathe through, and pendulum both softens and spaces out. Over time subtler, more complex pendulum variants can appear, but by then awareness is usually high enough not to mistake them for truth. Sometimes there's even a paradoxical read of "nothing's happening anymore" - simply because the sharp pendulums have stopped showing up.

The early stage of the work also significantly cuts both the likelihood and intensity of later pendulum. Processing basic polarities and base reactions makes the whole system more stable. Which means skimming through stage one shallow can end up costing more later, once heavier automated work kicks in.

And finally: there's no guarantee you'll hit severe pendulum. Fully individual, strongly tied to pace. Higher rate of change, higher risk of temporary destabilization. Everyone weighs their own tolerance for temporary discomfort against how badly they want a more stable end state - and makes their own call.

One purpose of this chapter is filtering out people not ready for this kind of work. Not a judgment, just a statement of fact. If you're ready but hesitant after reading all this, remember words of Akiko Yosano: **“****They told me that this road would take me to the ocean of death, and so, halfway there, I turned back. Since then, crooked, dark, roundabout paths have stretched out before me.******”****

No pendulum breaks someone who's made a real decision to go the distance. Patience and willpower don't produce miracles - they just let the process actually reach completion.

One last reminder.

Any pendulum is a distortion of perception, generated by activated automatic patterns. Its content is never to be taken as truth.

---

[Previous: Instructions for the Subconscious](09-instructions-for-the-subconscious.md) | [Book contents](../README.md) | [Next: Philosophical Aspects of the System](11-philosophical-aspects-of-the-system.md)
