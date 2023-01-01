---
description: by Will Larson
---

# Staff Engineer: leadership beyond the management track

> _Being a Staff-engineer is not just a role. It’s the intersection of the role, your behaviors, your impact, and the organization’s recognition of all those things._

#### Staff Engineer archetypes

* <mark style="background-color:yellow;">**The Tech Lead**</mark>** ** guides the approach and execution of a particular team. They partner closely with a single manager, but sometimes they partner with two or three managers within a focused area.
* <mark style="background-color:yellow;">**The Architect**</mark>** ** is responsible for the direction, quality, and approach within a critical area
  * they combine in-depth knowledge of technical constraints, user needs, and organization level leadership.
  * architects are responsible for the success of a specific technical domain within their company, for example, the company’s API design, frontend stack, storage strategy, or cloud infrastructure. For a domain to merit an Architect, it must be both complex and enduringly central to the company’s success.
* <mark style="background-color:yellow;">**The Solver**</mark>** ** digs deep into arbitrarily complex problems and finds an appropriate path forward. Some focus on a given area for long periods. Others bounce from hotspot to hotspot as guided by organizational leadership.
  * The Solver is a trusted agent of the organization who goes deep into knotty problems, continuing to work on them until they’re resolved. Folks in this role are moved onto problems identified by organizational leadership as critical and either lacking a clear approach or with a high degree of execution risk.
* <mark style="background-color:yellow;">**The Right Hand**</mark>** ** extends an executive’s attention, borrowing their scope and authority to operate particularly complex organizations. They provide additional leadership bandwidth to leaders of large-scale organizations.
  * Folks in this role attend their leader’s staff meetings and work to scale that leader’s impact by removing important problems from their plate. Problems addressed at this level are never purely technical and instead involve the intersection of the business, technology, people, culture, and process.

#### Responsibilities

* <mark style="background-color:yellow;">**setting and editing technical direction**</mark>** **&#x20;
  * write an engineering strategy to guide your organization’s approach to supporting your company’s business objectives with its architecture, technology selection, and organizational structure.
  * curate technical quality to maintain the quality of your company’s architecture and software as it grows and tacks over time.
* <mark style="background-color:yellow;">**providing sponsorship and mentorship**</mark>
  * create space for others so that your team grows stronger than your contribution.
* <mark style="background-color:yellow;">**injecting engineering context into organizational decisions, exploration**</mark>
* <mark style="background-color:yellow;">**being glue**</mark>** ** (as Tanya Reilly calls it)
* <mark style="background-color:yellow;">**impact/energy**</mark> - work on what matters to make the most of the working hours you have, particularly as you get further along in your career and life’s commitments expand.&#x20;

> I’ve taken to using the word “energized” over “impactful.” “Impactful” feels company-centric, and while that’s important, “energized” is more inwards-looking. Finding energizing work is what has kept me at Stripe for so long, pursuing impactful work. - Michelle Bu

* <mark style="background-color:yellow;">**alignment with leadership**</mark> - stay aligned with authority to remain an effective leader over time.
  * Technical leadership roles rely on proxied authority from another (usually, managerial) leader, and continued access to that authority depends on staying aligned, trustworthy, and predictable. To lead, you have to follow. Having a vivid sense of how things ought to work is a powerful leadership tool, but it’s also essential to learn to blend your vision with the visions from your peers and leadership.
* <mark style="background-color:yellow;">**collaboration**</mark> - stop spending your social capital repairing relationships frayed by conflict, and learn to collaborate with folks with different priorities and perspectives.
  * build a network of peers to vet difficult decisions and to give you honest feedback when your role’s authority starts to temper feedback.

#### What to work on

* <mark style="background-color:yellow;">**impact work valued by the org**</mark> - explore whether your company is experiencing an <mark style="color:yellow;">**existential risk**</mark>** ** - Companies operate in an eternal iterative elimination tournament, balancing future success against surviving until that future becomes the present. If you’re about to lose one of those rounds, then always focus there. Running out of money, like my experience at Digg, can be the most obvious issue, but not every existential issue is financial, like Twitter’s fail whale stability challenges or adapting to the shifts caused by the Covid-19 pandemic.
* <mark style="background-color:yellow;">**impact work not valued by the org**</mark> - Sometimes you’ll find work that’s worthy of attention but which an organization is incapable of paying attention to, usually because its leadership doesn’t value that work. In some companies, this is <mark style="color:yellow;">**developer tooling work**</mark>. In others, it’s <mark style="color:yellow;">**inclusion work**</mark>. In most companies, it’s <mark style="color:yellow;">**glue work**</mark>.
  * Teaching a company to value something it doesn’t care about is the hardest sort of work you can do, and it often fails, so you should do as little of it as you can, but no less.
* <mark style="background-color:yellow;">**team growth**</mark>** ** - One area that’s often underinvested in (e.g., lots of room to work in) while also being highly leveraged is <mark style="color:yellow;">**growing the team around you**</mark>. Hiring has a lot of folks involved in it, usually in terms of optimizing the hiring funnel, but onboarding, mentoring, and coaching are wholly neglected at many companies despite being at least as impactful as hiring to your company’s engineering velocity.
* <mark style="background-color:yellow;">**getting work finished/unblocking**</mark> - A surprising number of projects are one small change away from succeeding, one quick modification away from unlocking a new opportunity, or one conversation away from consensus. I think of making those <mark style="color:yellow;">**small changes, quick modifications, and short conversations as editing your team’s approach**</mark>.
  * One special sort of editing is helping finish a project that just can’t quite close itself out. Often you’ll have a talented engineer earlier in their career who is already doing the work but can’t quite create buy-in or figure out how to rescope their project into finishable work. It’s surprisingly common that coaching a teammate on how to tweak a project into something finishable and then lending them your privilege to budge the right friction points will transform a six-month slog into a two-week sprint with almost an identical impact.
* <mark style="background-color:yellow;">**manage technical quality**</mark>
  * <mark style="color:yellow;">**fix the hot spots**</mark> that are causing immediate problems&#x20;
  * <mark style="color:yellow;">**adopt best practices**</mark> that are known to improve quality&#x20;
    * measure the problem at hand, identify where the bulk of the issue occurs, and focus on precisely that area.
    * limit yourself to a single best practice rollout at any given time.
  * <mark style="color:yellow;">**align technical vectors**</mark> in how your organization changes software&#x20;
  * <mark style="color:yellow;">**measure technical quality**</mark> to guide deeper investment&#x20;
  * <mark style="color:yellow;">**spin up a technical quality team**</mark> to create systems and tools for quality&#x20;
  * <mark style="color:yellow;">**run a quality program**</mark> to measure, track and create accountability
  * <mark style="color:yellow;">**invest in quality leverage points**</mark>. The three most impactful points are:&#x20;
    * <mark style="color:yellow;">**interfaces**</mark> = contracts between systems
      * Effective interfaces decouple clients from the encapsulated implementation.
      * Durable interfaces expose all the underlying essential complexity and none of the underlying accidental complexity.&#x20;
      * Delightful interfaces are eagerly discerning, discerningly eager.
    * <mark style="color:yellow;">**state**</mark> - gets complex faster than other systems and has an inertia that makes it relatively expensive to improve later.&#x20;
      * As you incorporate business obligations around security, privacy, and compliance, changing your stateful systems becomes even more challenging.
    * <mark style="color:yellow;">**data models**</mark> = the intersection of the interfaces and state, constraining your stateful system’s capabilities down to what your application considers legal.&#x20;
      * A good data model is rigid: it only exposes what it genuinely supports and prevents invalid states’ expression.&#x20;
      * A good data model is tolerant of evolution over time.&#x20;
      * Effective data models are not even slightly clever.
  * noticing problems and acting on solving them proactively, instead of letting them go.

#### What to avoid

* <mark style="background-color:yellow;">**snacking**</mark>
  * Hunter Walk recommends that folks avoid “snacking” when they prioritize work. If you’re in a well-run organization, at some point, you’re going to run out of things that are both high-impact and easy. This leaves you with a choice between shifting right to hard and high-impact or shifting down to easy and low-impact. The latter choice–easy and low-impact–is what Walk refers to as snacking.
* <mark style="background-color:yellow;">**preening**</mark>
  * Preening is doing low-impact, high-visibility work. Many companies conflate high-visibility and high-impact so strongly that they can’t distinguish between preening and impact, which is why it’s not uncommon to see some companies’ senior-most engineers spend the majority of their time doing work that’s of dubious value, but that is frequently recognized in company meetings.
* <mark style="background-color:yellow;">**chasing ghosts**</mark>** ** - not being aligned with what the company values&#x20;
  * Dig into what a company values and ensure it aligns with your intended personal growth. If a company’s leadership consists entirely of folks who focus their energy on performative urgency or acts of fealty, don’t be surprised when your success in the company depends on those activities.
  * It’s surprisingly common for a new senior leader to join a company and immediately drive a strategy shift that fundamentally misunderstands the challenges at hand. The ghosts of their previous situation hold such a firm grasp on their understanding of the new company that they misjudge the familiar as the essential.

#### Writing an engineering vision/strategy

To write an engineering vision, write <mark style="color:yellow;">**five engineering strategies**</mark>, and forecast their implications two years into the future.&#x20;

* Take five of your recent strategies, extrapolate how their tradeoffs will play out over the next two to three years. As you edit through the contradictions and weave the threads together, you’ve written an engineering vision.
* The final version will give you what Tanya Reilly calls a robust belief in the future, which makes it easier to understand how your existing strategies relate to each other and simplifies writing new strategies that stand the test of time.
* For a useful vision, a few things to focus on are:&#x20;
  *   <mark style="background-color:yellow;">**Write two to three years out**</mark>** ** - Companies, organizations, and technology all change quickly enough that thinking too far into the future is fraught. It also doesn’t work if you

      write a vision that expires in six months–how many strategies would you realistically write within that six- month window? Try to focus on two to three years out; you can expand that horizon a bit if you’re a fairly established company.&#x20;
  * <mark style="background-color:yellow;">**Ground in your business and your users**</mark>** ** - Effective visions ground themselves in serving your users and your business. That tight connection keeps the vision aligned with your leadership team’s core values–users and business. Bad visions treat technical sophistication as a self-justifying raison d’être–a view that is never shared by your company’s leadership.
  * <mark style="background-color:yellow;">**Be optimistic rather than audacious**</mark> - Visions should be ambitious, but they shouldn’t be audacious. They should be possible, but the best possible version if possible. Do write what you could accomplish if every project is finished on time and without major setbacks. Don’t write what you think would be possible with infinite resources.&#x20;
  * <mark style="background-color:yellow;">**Stay concrete and specific**</mark> - Visions get more useful as they get more specific. Generic statements are easy to agree with but don’t help reconcile conflicting strategies. Be a bit more detailed than you’re comfortable with. Details in visions are often illustrative rather than declarative, giving a taste of the future’s flavor rather than offering a binding commitment.&#x20;
  * <mark style="background-color:yellow;">**Keep it one to two pages long**</mark>** ** - The reality is that most people don’t read long documents. If you write something five or six pages long, readers will start dropping off without finishing it (or will skim it very rapidly without engaging with the details). Force yourself to write something compact, and reference extra context by linking to other documents for the subset of folks who want the full details.

To write an engineering strategy, write <mark style="color:yellow;">**five design documents**</mark>, and pull the similarities out.

* Good strategies guide tradeoffs and explain the rationale behind that guidance. Bad strategies state a policy without explanation, which decouples them from the context they were made.
* resources - [Developing a framework for responsible innovation](https://discovery.ucl.ac.uk/id/eprint/1393388/1/Stilgoe\_Research\_Policy.pdf), [How Big Technical Changes Happen at Slack](https://slack.engineering/how-big-technical-changes-happen-at-slack/), [Good Strategy, Bad Strategy](https://www.amazon.com/Good-Strategy-Bad-Difference-Matters/dp/0307886239)
* _“When should we write design documents?”_ is a strategy worth writing. _“Which databases do we use for which use cases?”_ is a strategy worth writing. _“How should we stage our migration from monolith to services?”_ is worth writing, too.

How

* <mark style="background-color:yellow;">**Start where you are**</mark>** ** - it’s easy to be paralyzed by the inherently vast ambiguity we work in, but you’ve just got to dive in and start writing.&#x20;
  * Waiting for missing information doesn’t work: every missing document is missing for a good reason. Whatever you write will need to change, and if you write something particularly bad, you’ll quickly realize the need to change it. Where you are now is always the best place to start.&#x20;
* <mark style="background-color:yellow;">**Write the specifics**</mark>** ** - write until you start to generalize, and then stop writing.
  * If you can’t be specific, wait until you’ve written more design documents. Specific statements create alignment; generic statements create the illusion of alignment.&#x20;
* <mark style="background-color:yellow;">**Be opinionated**</mark> - good strategies are opinionated.&#x20;
  * If they aren’t opinionated, then they won’t provide any clarity on decision making. However, being opinionated on its own isn’t enough. You also need to show your work. Show your work. You must show the rationale behind your opinions. Showing your work builds confidence in the first version of a document, but even more importantly, by showing your work, you make it possible for others to modify and extend your work as the underlying context shifts.

#### Writing a design document

> _Design documents have what bad strategies lack: detailed specifics grounded in reality._

When

* for any project whose capabilities will be used by numerous future projects.
* for projects that meaningfully impact your users.
* or any work taking more than a month of engineering time.

How

* <mark style="background-color:yellow;">**Start from the problem**</mark>
  * The clearer the problem statement, the more obvious the solutions.
  * If solutions aren’t obvious, spend more time clarifying the problem.&#x20;
  * If you’re stuck articulating the problem, show what you have to five people and ask them what’s missing: fresh eyes always see the truth.&#x20;
* <mark style="background-color:yellow;">**Keep the template simple**</mark>
  * Most companies have a design document template, which is a great pattern to follow. However, those templates are often expanded to serve too many goals.&#x20;
  * Overloaded templates discourage folks from writing design documents in the first place.
  * Prefer minimal design document templates that allow authors to select the most useful sections and only insist on exhaustive details for the riskiest projects.&#x20;
* <mark style="background-color:yellow;">**Gather and review together, write alone**</mark>
  * It’s very unlikely that you personally have all the relevant context to write the best design document on a given topic.&#x20;
  * Before getting far into the process, collect input from folks with relevant perspectives, particularly those who will rely on the output of your design document. However, be skeptical of carrying that collaborative.
  * Look for controversial decisions that came up in multiple designs, particularly those that were hard to agree on.

#### Aligning technical decisions

* <mark style="background-color:yellow;">**Give direct feedback**</mark>&#x20;
  * start with simply giving direct feedback to the individuals who you believe are misaligned. As much as they’re missing your context, you’re missing theirs, and a quick conversation can often prevent years of unnecessary process.&#x20;
* <mark style="background-color:yellow;">**Refine your engineering strategy from tech spec, to strategy, to vision**</mark>&#x20;
  * <mark style="color:yellow;">**Encapsulate your approach in your workflows and tooling**</mark>. Documentation of a clear vision is helpful, but some folks simply won’t study your document.&#x20;
  * Deliberate tools <mark style="color:yellow;">**create workflows that nurture habits**</mark> far better than training and documentation. For example, provisioning a new service might require going to a website that requires you to add a link to a technical spec for that service. Another approach might be blocking deploys to production if the service doesn’t have an on-call setup established, with someone currently on-call, and that individual must also have their push notifications enabled.
* <mark style="background-color:yellow;">**Train new team members during their onboarding**</mark>. Changing folks’ habits after they’ve formed is quite challenging, which is frustrating if you’re attempting to get folks to adopt new practices. However, if you get folks pointed in the right direction when they join, then that habit-momentum will work in favor of remaining aligned.&#x20;
* <mark style="background-color:yellow;">**Use Conway’s Law**</mark> - Conway’s Law argues that organizations build software that reflects their structure. If your organization is poorly structured, this will lead to tightly coupled or tangled software. However, it’s also a force for quality if your organization’s design is an effective one.
* <mark style="background-color:yellow;">**Curate technology change using architecture reviews, investment strategies, and a structured process for adopting new tools**</mark>. Most misalignment comes from missing context, and these are the organizational leverage points to inject context into decision-making. Many organizations start here, but it’s the last box of tools that I recommend opening. How can you provide consistent architecture reviews without an articulated vision? Why tell folks your strategy after they’ve designed something rather than in their onboarding process?
* <mark style="background-color:yellow;">**Trust metrics over intuition**</mark> - You should have a way to measure every project.&#x20;
* Establish a thoughtful approach that balances the benefits of exploration against the benefits of standardization.

#### Operating organizational programs

Approach:

* <mark style="background-color:yellow;">**Identify a program sponsor**</mark> - You can’t change an organization’s behavior without an empowered sponsor. Organizations behave the way they do because it’s the optimal solution to their current constraints, and you can’t shift those constraints without the advocacy of someone powerful.
* <mark style="background-color:yellow;">**Generate sustainable, reproducible metrics**</mark>** ** - It’s common for folks running a program to spend four-plus hours a week maintaining their dataset by hand. This doesn’t work. Your data will have holes in it, you won’t be able to integrate your data with automation in later steps, and you’ll run out of energy to do the work to effect real change; refreshing a metrics dashboard has no inherent value.
* <mark style="background-color:yellow;">**Identify program goals for every impacted team and a clear path for them to accomplish those goals**</mark>** -** Your program has to identify specific goals for each impacted team. For example, reducing test flakiness in their tests or closing incident remediations more quickly. However, it’s essential that you provide the map to success! So many programs demand participation from other teams without providing clear directions on how they can accomplish their part. The program owner is the subject matter expert, don’t offload your strategy to every team to independently reinvent.
* <mark style="background-color:yellow;">**Build the tools and documentation to support teams towards their goals**</mark>** -** Once you’ve identified a clear path for teams to accomplish your program goals, figure out how you can help them make those changes! This might be providing “golden examples” of what things ought to look like, or an example pull request refactoring a challenging section of code into the new pattern. It might be providing a test script to verify the migration worked correctly. It might be auto-generating the conversion commit to test, verify, and merge without having engineers write it themselves. Do as much as you possibly can to avoid every team having to deeply understand the problem space you’re attempting to make progress in.&#x20;
* <mark style="background-color:yellow;">**Create a goal dashboard and share it widely**</mark>** -** Once you have your program goals communicated to each team, provide dashboards that help them understand their current state, their goal state, and that give reinforcing feedback on their (hopeful) progress along the way. The best dashboard is going to be both a scorecard for each team’s work and also provide breadcrumbs for each team on where to focus their next efforts. There are three distinct zoom-levels that your dashboard should support. The fully zoomed-out level helps you evaluate your program’s impact. The fully zoomed-in level helps an individual team understand their remaining work. A third level between the two helps organizational leaders hold their teams accountable (and supports your program sponsor in making concrete, specific asks to hold those leaders accountable).
* <mark style="background-color:yellow;">**Send programmatic nudges for folks behind on their goals.**</mark> Folks are busy. They won’t always prioritize your program’s goals. Alternatively, they might do an amazing job of making your requested improvements but backtrack later with deprecated practices. Use nudges to direct the attention of teams towards the next work they should take towards your program’s goals. Remember, attention is a scarce resource! If you waste folks’ time with a nudge email or ping, they won’t pay attention to the next one.
* <mark style="background-color:yellow;">**Periodically review program status with your sponsor.**</mark> Programs are trying to make progress on an organizational priority that doesn’t naturally align with the teams’ goals. Many teams struggle to break from their local prioritization to accomplish global priorities. This is where it’s essential to review your overall progress with your sponsor and point them towards the teams that prioritize program work. Effectively leveraging your sponsor to bridge misaligned prioritization will be essential to your success.

The three leading causes of failed programs are:

* running it purely from a process perspective and becoming detached from the reality of what you’re trying to accomplish
* running it purely from a technical perspective and thinking that you can skip the essential steps of advocating for your goal and listening to the folks you’re trying to motivate
* trying to cover both perspectives as a single person–don’t go it alone!

The two most effective ways to deal with jerks are:

* including someone they can’t be a jerk to in the meeting (like their manager or the CTO)
* investing heavily into aligning with them before the meeting, so they feel heard and are less likely to derail the discussion

#### Managing staff engineers

* <mark style="background-color:yellow;">**Sponsor and support more than you direct.**</mark> If you’re giving daily direction to your Staff engineers, you’re utilizing them in the wrong roles. If you aren’t giving them weekly feedback, you’re delaying their growth. If you aren’t lending your sponsorship to their initiatives, then you’ll train the initiative out of them. Help them rewire their definition of success. Working in a high-performing product engineering team is a flywheel of positive feedback. Your product manager appreciates your work. Your engineering manager engages the team. Your peers enjoy working together. Your users love your product. Your business loves the user adoption. Conversely, the Staff engineer’s flywheel of feedback is a lot less immediate. You spend more time working through conflict. You work on longer time horizons. You’re representing important priorities that require deprioritizing some business or product goals. Many folks don’t address this shift and wake up a year later hating their new role, and as their manager, you can help them recognize this shift and find compensating strategies to remain energized.
* <mark style="background-color:yellow;">**Give feedback.**</mark> One particularly important strategy for rewriting their definition of success—and to keep them growing—is to give frequent feedback. If they’ve picked the wrong battle, tell them, and tell them why. If they’re prioritizing work you wouldn’t, tell them, and tell them why. Nothing is more stressful for a high performer than not knowing how they’re doing! If you don’t give feedback, especially about their best work, they’ll keep changing their approach until you do give feedback (often to your regret).
* <mark style="background-color:yellow;">**Keep them informed.**</mark> As a manager, it can be easy to forget how much more access you have to information than the engineers you work with. The reality is that most organizations build their information flows around managers communicating key information to other managers. Your Staff-plus engineers will be hamstrung if you don’t find a deliberate, reproducible process for sharing your context with them. Some folks do this at the beginning of their 1:1s, which works OK, but I’ve come to prefer dropping them into the team’s chat channel as they happen and aggregating them into my weekly email update. Involve them in planning and prioritization. Many engineers get frustrated that “the right work never gets prioritized,” and one of the best solutions to this is to proactively involve more engineers in the planning process. This works on two fronts. First, they understand more of the competing work and why that work is important, and second, they’ll be present to advocate more effectively for the sorts of technical work they see missing. Agree on how to stay aligned while acting independently. As you push Staff-plus engineers you support towards leadership, they’re going to start leading more, which will sometimes include surprising you. If leaders you work with never surprise you, then you’re not delegating enough, but if they frequently surprise you, it may be helpful to explicitly establish your controls.
* <mark style="background-color:yellow;">**Create space for them to think without detaching them from the day-to-day realities of the organization.**</mark> Many folks in these roles are so motivated by impact and “doing the right thing for the business” that they’ll grind themselves down without external intervention. If you’re their manager, then “external intervention” means you. If you see them spending too much time firefighting and helping unblock urgent work, work with them to protect more time for deep thinking work as well. Conversely, if you see them only doing deep thinking work, they’re likely to lose context and potentially the respect of their peers and the business if they don’t adjust that mix. Remind them they’re a role model. Much like they do for managers, engineers in an organization watch Staff-plus engineers to learn which behavior and actions are rewarded (and tolerated). This is a great responsibility, but also a huge opportunity for impact: by living positive values, they have the opportunity to create a positive organization around them.
* <mark style="background-color:yellow;">**Minimize manager overflow.**</mark>** ** In the quest for efficiency over effectiveness, many companies trap their managers in a staggering amount of coordination and bureaucracy. When you’re drowning, you’re going to look for help wherever you can, and in many cases, that causes managers to offload management work to their Staff engineers. This is absolutely going to happen sometimes– your relationship with Staff-plus engineers you manage is a partnership–but try very hard to minimize the amount and ensure it’s a temporary overflow rather than a permanent one.
* <mark style="background-color:yellow;">**Give them unrefined problems.**</mark> This is a senior role where you ought to give them a problem space that they narrow into a more specific problem and solution. They have better technical context than you do, and if you point them too precisely at what you think is the problem, you won’t benefit from their judgment. Picking precisely the right problem creates at least as much impact as finding precisely the right solution, and is only possible when you create space.
* <mark style="background-color:yellow;">**Cede space to their leadership.**</mark> When you’re managing a Staff-plus engineer, find ways to move pieces of your ownership explicitly into their realm of responsibility. For example, how can you enable them to hold their team responsible for technical quality, rather than you doing it? This creates leverage for both of you and a sense of ownership for the Staff-plus engineer.
* <mark style="background-color:yellow;">**Appreciate them.**</mark> Great Staff-plus engineers operate fairly independently, so it can be easy to deprioritize them when the organization is on fire. Ignoring your most important people is the manager version of “snacking”–something that feels important but usually isn’t the right priority. So keep your 1:1s, and generally remember to show up for them, especially if they aren’t the sort of person to demand it. Build and insist upon alignment with the business. Some engineers succeed despite harboring a mentality that technical work is more important than the business requiring that work. This mentality is generally toxic, but it is exceptionally toxic when held by a Staff-plus engineer. This is someone who is a role model for the wider organization, and stretching them beyond that perspective is essential for them to remain in a leadership role. Companies undermine and eventually eject leaders who are misaligned with the business.
* <mark style="background-color:yellow;">**Hold them responsible for the full role.**</mark> While few folks reach Staff-plus roles with major technical weaknesses, it’s my lived experience that many folks reach these roles hampered by significant leadership or behavioral challenges. These folks get the title but tend to linger in Staff purgatory where they’re expected to lead but are kept away from most leadership opportunities. They’re viewed as too unreliable or “expensive to involve.” You’ve got to give these folks feedback on their gaps and hold them accountable to the full role expectations. Don’t let them linger as quasi-leaders indefinitely. Maybe they initially got the role via title inflation, so you decide to just cover for their gaps instead of fixing it–don’t do that, instead, figure out a plan to support them while shifting that responsibility to them.
* <mark style="background-color:yellow;">**Give them access to the room but don’t treat it as a status symbol.**</mark> Folks often get fixated on status symbols, and one that’s particularly common for engineers to focus on is “being in the room.” Sometimes meetings are where the work happens, but most routine reporting meetings have too many people in them, and you can create a great deal of time and space for both you and the Staff-plus engineer you’re supporting by sharding attendance across various meetings rather than doubling up for all of them.

#### Suggested Resources

Blogs:

* staff engineer responsibilities:
  * [What Does Sponsorship Look Like? - Lara Hogan](https://larahogan.me/blog/what-sponsorship-looks-like/)
  * [Being Glue - Tanya Reilly](https://noidea.dog/glue)
* org strategy:
  * [Developing a framework for responsible innovation](https://discovery.ucl.ac.uk/id/eprint/1393388/1/Stilgoe\_Research\_Policy.pdf)
  * [How Big Technical Changes Happen at Slack](https://slack.engineering/how-big-technical-changes-happen-at-slack/)
  * [Good Strategy, Bad Strategy](https://www.amazon.com/Good-Strategy-Bad-Difference-Matters/dp/0307886239)

Books:

* Resilient Management - Lara Hogan
* High Output Management - Andrew Grove
