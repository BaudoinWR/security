## Testing software
<hr />

--

## SSDLC
<hr />

![](pics/bug_cost.jpg)<!-- .element style="z-index: -100; box-shadow:none; position: fixed; left: 40px; top: 130px; width: 750px;" class="fragment" data-fragment-index="0" -->
![](pics/ssdlc/SDLC.png)<!-- .element style="box-shadow:none; position: fixed; left: 100px; top: 400px; width: 800px; " -->

![](pics/ssdlc/SSDLC_Risk.png)<!-- .element style="box-shadow:none; position: fixed; left: 130px; top: 320px;" class="fragment" data-fragment-index="2" -->
![](pics/ssdlc/SSDLC_Threat.png)<!-- .element style="box-shadow:none; position: fixed; left: 240px; top: 320px;" class="fragment" data-fragment-index="2" -->
![](pics/ssdlc/SSDLC_Static.png)<!-- .element style="box-shadow:none; position: fixed; left: 350px; top: 320px;" class="fragment" data-fragment-index="2" -->
![](pics/ssdlc/SSDLC_Dynamic.png)<!-- .element style="box-shadow:none; position: fixed; left: 460px; top: 320px;" class="fragment" data-fragment-index="2" -->
![](pics/ssdlc/SSDLC_Pentest.png)<!-- .element style="box-shadow:none; position: fixed; left: 570px; top: 320px;" class="fragment" data-fragment-index="1" -->
![](pics/ssdlc/SSDLC_Config.png)<!-- .element style="box-shadow:none; position: fixed; left: 680px; top: 320px;" class="fragment" data-fragment-index="2" -->
![](pics/ssdlc/SSDLC_Cleanup.png)<!-- .element style="box-shadow:none; position: fixed; left: 780px; top: 320px;" class="fragment" data-fragment-index="2" -->

![](pics/ssdlc/SSDLC_Left.png)<!-- .element style="box-shadow:none; position: fixed; left: 300px; top: 220px;" class="fragment" data-fragment-index="3" -->

--

## Testing
<hr />

### Five ways

1. Internal testing
2. Pentest
3. Bug Bounty Program
4. Responsible Disclosures
5. Say "It's unhackable"

-- Notes --

Five main ways to test your software product:
1. Make developers test their own software
2. Hire pentesters to do this (most common way)
4. Use a bug-bounty platform (private or public)
3. Have a responsible disclosure policy and hope someone (everyone) uses it
5. Say your product or service is unhackable

--

## Testing
<hr />

### Criteria

* Effort
* Control
* Cost
* Exposure

-- Notes --

* Effort: How much effort to set up / initiate
* Control: How much control over testing / testers
* Cost: How much cost to set up / initiate including results / consequences
* Exposure: How much exposure to outside it generates

--

## Unhackable
<hr />

![](pics/testing/unhackable.jpg)<!-- .element style="box-shadow:none; position: fixed; right: 50px; top: 50px;"  -->

-- Notes --

5. Say your product or service is unhackable

These "promises" are like a red cloth for a horde of bulls: They will storm it and take it down.

--

## Unhackable
<hr />

![](pics/testing/unhackable_pr.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 150px;"  -->

-- Notes --

* It does give you free pen-tests, yes, but at what cost?
* Bad PR, no PenTest report, no decent coverage, no handover

--

## Unhackable
<hr />

### Bitfi

![](pics/testing/BitFi.png)<!-- .element style="box-shadow:none; position: fixed; right: 50px; top: 50px; width: 400px;"  -->
![](pics/testing/BitFi_no_weaknesses.png)<!-- .element style="box-shadow:none; position: fixed; left: 50px; bottom: 50px;"  -->

-- Notes --

* Example:
  * BitFi launched Cryptocurrency-wallet with no security weaknesses
  * Technically, they didn't say it was unhackable

--

## Unhackable
<hr />

### Bitfi

![](pics/testing/BitFi_promise.png)

-- Notes --
* Until someone else did it for them, backer McAfee (yes, from the security company)

--

## Unhackable
<hr />

### Bitfi

![](pics/testing/BitFi_hacked.png)<!-- .element style="box-shadow:none; position: fixed; right: 50px; top: 50px;"  -->

-- Notes --
And then the expected happened, when the wallet got hacked


--

## Unhackable
<hr />

### Bitfi

![](pics/testing/BitFi_concession.png)

-- Notes --
After which they admitted it wasn't the best idea


--

## Unhackable
<hr />

### Bitfi

![](pics/testing/BitFi_profile.png)

-- Notes --
But they still claim something, except it's not verified for accuracy 

--

## Unhackable
<hr />

![](pics/testing/unhackable.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 150px;"  -->

-- Notes --

* In conclusion, testing by claiming unhackable requires no effort and you get lots of free exposure.
* But it comes at a high cost and you have no control over the process.

--

## Pentest
<hr />

![](pics/hat_white.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 150px;"  -->

-- Notes --


2. Hire pentesters to do this (most common way)

In contrast: a professional pentest can be:
* controlled, with minimal to no exposure (NDA is standard)
* Also requires minimal effort (call a pentest-company, sign a contract, pay some money)
* Does cost a bit, but you get good to excellent pentest-reports with advise on mitigation strategy / actions

--

## Pentest
<hr />

![](pics/testing/external_pentest.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 150px;"  -->

--

## Internal Testing
<hr />

![](pics/testing/internal_testing.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 150px;"  -->

-- Notes --

1. Make developers test their own software

Doing this with your internal team can decrease the monetary cost, but:
* requires lots of efforts to get your team on the required level
* You have virtually total control and no exposure outside the company (except leaks or if you choose to expose / transparency)


--

## Bug Bounties
<hr />

![](./pics/hackerone.png)<!-- .element style="position: fixed; width: 150px; top: 70px; right: 50px; background-color: #ffffff;" -->
![](./pics/zerocopter.jpg)<!-- .element style="position: fixed; width: 150px; top: 140px; right: 170px; background-color: #ffffff;"  -->
![](./pics/bugcrowd.jpeg)<!-- .element style="position: fixed; width: 150px; top: 210px; right: 0px; background-color: #ffffff;"  -->

![](./pics/try_to_hack.png)<!-- .element style="position: fixed; width: 850px; bottom: 50px; lefty: 40px;" class="fragment" data-fragment-index="0" -->

-- Notes --

4. Use a bug-bounty platform (private or public)

* A bug-bounty program can supply much cheaper pentesting (bug-based payout), but you have to have decent baseline security or you'll still get bombarded with bugs
* You also have to have process in place to respond and mitigate bugs
* Control is reasonable, you could go private or public bounty program. Control follows the quality of mitigation process quality
  * Control is less when dealing with inexperienced bounty-hunters, so learn to deal (in positive ways) with those
  * Learn how these bug-bounty hunters think, extend a hand way forward to them

--

## Bug Bounties
<hr />

![](./pics/testing/hacker1.png)<!-- .element style="position: fixed; width: 850px; top: 70px; right: 50px; background-color: #ffffff;" -->

--

## Bug Bounties
<hr />

![](pics/testing/bug_bounty_program.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 150px;"  -->


--

## Responsible Disclosure
<hr />

![](pics/testing/security.txt.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 150px;"  -->

-- Notes --

3. Have a responsible disclosure policy and hope someone (everyone) uses it

* Effort setting up is easy: security.txt and fo
  * Effort to handle is dependent on dev-team's ability to communicate with bug-reporters and fix bugs
* Control depends on responsible disclosure rules (make them easy to read, though clear on feasible requirements)
  * Make sure you can fix bugs within short time-frame
  * Fixing in very short time-frame is PR bonus
* Cost depends on bounties:
  * Geeky shirts and stickers are cool, but product and $$$ are better. Doesn't have to be $100k budget (unless you're Google / Facebook)
* Exposure depends on product, PR, handling etc.
  * If you handle it badly, you WILL get exposure
  * If you have a security-related product, you WILL get exposure: see BitFi, but also Tesla, secure USB's etc.
  
* Just add a formatted test-file to your site, add a nicely formatted page as well, and your good to go.
* Wait: also add that response and mitigation process, because you also need it with this
* Control is again: reasonable, as long as you respond quickly and reach out to security community, talk THEIR language
* Cost is quite low. If you're a tech-company, think about paying in shirts, stickers or product, if it fits tech-savvy security researchers.
* Do mind that you could get exposure, but you indirectly influence whether that will be negative or positive (again, depends on quality of response process)

--

## Responsible Disclosure
<hr />

![](pics/testing/resposible_disclosure.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 150px;"  -->


--

## Testing
<hr />

### Control vs exposure

![](pics/testing/testing_control_vs_exposure.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 200px;"  -->

-- Notes --

* With more exposure comes less control
* Saying you're unhackable is basically the bullseye on your head

--

## Testing
<hr />

### Cost vs effort

![](pics/testing/testing_cost_vs_effort.png)<!-- .element style="box-shadow:none; position: fixed; left: 150px; top: 200px;"  -->

-- Notes --

* Effort to say you're unhackable is really low: post on Social media will land with the correct hackers very quickly
  * But costs will be high or gigantic, depending on how ethical they handle it
  * Prepare for PR backlash and bad publicity in news
* Initiating pentest is also easy: phone us, we'll do it for you
  * Running quality pentests that cover both low fruit and advanced attacks is expensive
* Having a responsible disclosure requires very little effort and cost:
  * Security.txt proposed standard at [IETF.org](https://tools.ietf.org/html/draft-foudil-securitytxt-06)
  * Generate one at [securitytxt.org](https://securitytxt.org/)
  * But handling them requires a business process to communicate between external researchers of various levels (in experience and communication) and development teams that should solve the issues
  * Cost could include small thank-you's from acknowledgements / mentions to stickers and t-shirts to products and bounties
* Bug bounties formalize and streamline responsible disclosure
  * Effort is again two parts: setting up and handling
  * Setup is a bit more than just a responsible disclosure, but platforms help with that
  * Handling is similar to responsible disclosure, so reuse that for both
  * Cost will be: fee's to Bug bounty platform and thank-you's mostly in form of bounties, but thank-you's, stickers, t-shirts and product for duplicates or low-level bugs will increase goodwill
  * Private bug-bounties should be aimed at experienced bug-hunters, which will result in more and higher bounty-payouts
  * Cost also depends on how good the base security is of what you like to test
* Internal is all about maturity of SSDLC
  * Start with awareness training for devs
  * Learn them how to [Hack yourself first](https://www.pluralsight.com/courses/hack-yourself-first)
  * That should fix low hanging fruit.
  * Have experienced pentesters test for advanced issues
  * Having automated security (unit-) tests is very helpful

--

## Testing
<hr />

### Advise

Set up bug-fixing process
  * Thorough
  * Integrated in SSDLC
  * Fast
  * Reliable

--

## Testing
<hr />

### Advise

1. Internal testing<!-- .element class="fragment" data-fragment-index="0" -->
2. External Pentesting<!-- .element class="fragment" data-fragment-index="1" -->
3. Private Bug-bounties<!-- .element class="fragment" data-fragment-index="2" -->
4. Public Bug-bounties<!-- .element class="fragment" data-fragment-index="3" -->

Add Responsible Disclosure if SSDLC is mature<!-- .element class="fragment" data-fragment-index="4" -->

--

## Testing
<hr />

### Advise

Embrace external researchers
* Acknowledge
* Cooperate
* Thank
* Never, EVER claim you're unhackable<!-- .element class="fragment" -->
