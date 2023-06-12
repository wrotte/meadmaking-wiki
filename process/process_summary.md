---
revision_id: 3c1b5fa8-c3f2-11ed-b22b-da060bb34abe
revision_date: 1678968067
---

##Process Summary

The purpose of this page is to be a resource for common questions on process that are not covered well in other sections, or to condense things down to the most important points. It is intended to be a resource for people who have read the rest of the wiki and are looking to bring it all together for improving their batches, or for making their first batch from an informed position. It tries to hammer all the basics together into one dense read and references the other pages when more detail is required. It's also a reference for me, /u/stormbeforedawn to copy paste into repeated questions on the subreddit. 




###Abreviations, slang and other lingo            


Abbreviation | Definition
---|---
ABV | Alcohol by volume
OG | Original gravity. Density measurement of potential alcohol
FG | Final gravity, the density of the finished mead. Converting the change between OG and FG gives ABV. 
SG | Any gravity measure. A powerful tool to diagnose a ferment's progress
1/3rd sugar | When 1/3rd of the sugar has been fermented. 1.090 to 1.060 SG would represent the change in a common must.
YAN | Yeast Assimilable Nitrogen. Yeast food. Nitrogen is yeast calories, but other micronutrients are important too.
PPM | Parts Per Million. Yeast food measurement typically.
Brix | The sugar content of a solution. One degree Brix is 1 gram of sucrose in 100 grams of solution.
SNA | Staggered Nutrient Addition. Adding nutrition over multiple steps to reduce spikes in temperature, colony growth or fermentation rate. 

   
###Using Meadcalc
[Meadcalc](http://meadcalc.freevar.com/) is the basic building block of making your own recipes and nutrition schedules. It gets you close to your starting gravity, which you will generally be verifying with a hydrometer. It reads about 1% potential ABV lower for a given specific gravity than Batchbuilder at 18%. [Batchbuilder](http://www.meadmakr.com/batch-buildr/) uses a different formula, and about .5% lower than a typical hydrometer. Which Calculator is the most accurate is up to some debate, but batchbuilder is generally considered to be the most accurate. You can read [here](http://www.fermcalc.com/fermcalc_alcohol.html#ucdavis) if you want to see all the methods for predicting and measuring ABV. It's trickier than you would expect. The long and short of it is that how much sugar is available to ferment in a must is a little complicated. When dissolving 1 gallon honey in 1 gallon water you actually get a little less than 2 gallons total volume. Chemistry is complicated, and the idea is to keep this tutorial simple. Meadcalc is one of the most powerful tools available at the moment, and it is free, and the errors at typical wine ABVs are negligible. Do take the numbers with a grain of salt from it and any other calculator when you approach dwójniak style recipes with nearly even amounts of honey and water and ~1.200 SGs. I will walk through the process of setting up and using meadcalc as a powerful brewing tool. If you are doing a traditional, or have no other fermentable sugars, consider using batchbuilder because of how well integrated it is with yeast selection, gravity, and nutrition. 

https://imgur.com/a/vjtXVGB Setting up Meadcalc

Here is a common batch set up. ~14% ABV, 5 gallons and 3 lbs honey per gallon. Note which boxes are checked. Increasing the sugar to 18lbs honey would result in a original gravity (OG) of 1.129. With a 14% yeast like D47 you could safely assume that you would end up with a sweet mead ~1.020 in final gravity (FG). Meadcalc can also handle fruit. It also handle’s fruit wrong quite happily if the user doesn’t use it right. Try adding 400 lbs of blackberry to a batch and watch the ABV break. The issue is that you need to account for the true wet volume of the must. If you add a gallon of blackberries to a batch you need to realize that a percentage of the addition is water as well as unfermentable solids. A gallon of berries weighs about 5 lbs and is about a quarter solids. Also, adding 10 lbs of blackberries to a 5 gallon batch is VERY different from adding honey and berries into a bucket and filling to 5 gallons. Here is an image of the Meadcalc set up correctly to account for the sugars of blackberries, less the volume of the solids. Solids that are unfermentable are typically around 25% of the total volume of fruit. This can vary quite widely depending on harvested ripeness and the type of fruit.

https://imgur.com/a/yNzizAV Meadcalc with berries

Note how the volume of the mead has been reduced. The fill volume is 5 gallons, but you lose about half a gallon. If you have the Brix of your fruit you can do the same thing with a blank sugar addition is you prefer. The fruit sugar contributions for Meadcalc are assumed averages, and fruit can vary greatly. Also, with larger loads of fruit solids a hydrometer becomes useless, it cannot measure the sugar and water contained within the berries. In order to use this tool correctly you need to know the brix of the puree or fruit you are adding, it's percent non fermenting solid, and how much volume a given weight takes up. These are are all easy to find numbers on the internet. 

For further reading here is the Brix of various fruit juices [Brix from Cornell](https://www.law.cornell.edu/cfr/text/19/151.91)

For reasonable estimates on fruit volume you can use this website or others like it [Fruit weight and volume converter](https://www.howmuchisin.com/produce_converters). Assuming 25% nonfermenting volume is a safe bet generally, but fruit that has little flesh can be as low as 5% non fermentable. When adding fruit, consider the brix of the fruit addition. There are discrepancies in sources on available fruit sugars that vary a lot based off of harvest time, variety, weather and harvesting method. Use your best judgment, the brix field can be edited as you see fit for a fruit addition. Juicing your own fruit and measuring brix with give you the most accurate OG estimates and eliminate the need to fudge volumes based on non fermenting volumes.

Further reading on Gotmead on the calculator and more info on the blending calcs is available here [Gotmead](http://gotmead.com/blog/mead-calculator-help/)

###Nutrition

Nitrogen is the building block of yeast nutrition. [Nutrients](/ingredients/nutrients) can be seen on the wiki explaining what each one is. 

Fermax is loosely fermaid K, and Fermaid A is Fermaid K without the fatty acids, and micronutrients. Wyeast Vintner's Choice is also similar. 

Fermaid O can be more or less approximated by boiling yeast hulls. 

DAP is one of the most common nutrients. It is white and granular. If you have a bag of "nutrient" it's probably this. It's a great nutrient up to 10% ABV and very cheap. LD Carlson "Nutrient" and "Energizer" are this, with the energizer having some micronutrients. They are not adequate for typical ABV must, and must be supplemented with organic nitrogen sources. 

GofermPE is a rehydration nutrient from Fermaid. Goferm is the older formulation of it and GofermPE is the newer which is phasing out the first. This blend contributes little to no nitrogen, but makes yeast far better at sucking up organic nitrogens like Fermaid O and helps prevent against a variety of stall mechanisms. 

Some yeast need more nutrition, some need less. [Here](http://www.piwine.com/media/pdf/yeast-selection-chart.pdf) is a great chart for determining your yeast's nutrition needs as well as ABV ranges. 

Using Goferm nutrient and an appropriate target yan can greatly reduce the risks of stalled batches and off flavors, as well as reducing the risk of infection. There are a lot of nutrition regimens out there, the largest being ToSNA, SNA, and a fermK based SNA. Any one of the three will get the job done when used with Goferm, and you will see a world of improvement in your brewing. 

###YAN calcs 
Proper nutrition is what sets a good mead maker apart from an inexperienced one. A good mead with good nutrition can be done and fit to drink in a quarter of the time with adequate YAN. Fruit and raisins add significant nitrogen when added at several pounds per gallon levels, but a handful of raisins is NOT a suitable replacement for real nutrition if your goals are the quickest, high quality and predictable turnarounds. Fruit, like raisins, can help a lot with mouthfeel and for making more complex flavors. There is a reason a lot of JAOM style meads use them. Dry, thin, low ABV meads with no tannin or acid are not often great meads. 

YAN stands for yeast assimilable nitrogen. The [whitepaper](https://docs.google.com/document/d/11pW-dC91OupCYKX-zld73ckg9ximXwxbmpLFOqv6JEk/edit) goes into great detail on nutrition. This section will explain how to use the [YAN nutrient calculator](https://docs.google.com/spreadsheets/d/1W8Pp52vFx9g-Uk7aq4WK66Kg_TI5nTrI32sBc5fGaPU/edit#gid=0). 

From the last section using meadcalc you have your OG. If you are finishing dry that’s all you need. If you are finishing 1.020+, consider reducing your OG for nutrient calculations. These yeast nutrient requirement calculations are derived from testing fermentation that was going relatively dry. If you want a 14% wine that you want to finish sweet at 1.040 you can ferment dry and then backsweeten. Some mead makers prefer to ferment all their honey rather than backsweeten. The final measurable fructose and sucrose ratio will be different in a backsweetened mead vs front loaded honey addition and this can make very small changes in the flavor. Since you are making the same amount of alcohol (14%) either way, for calculating how much nutrition you need you would use 1.105 (14% potential) as the OG for nutrient calcs, not the ~1.147 (18.6% potential) that your real must would be with all the honey added in primary. 

Armed with your SG, head to the YAN Nutrient Calculator. This is a powerful tool, much like [Meadmakr’s Advanced SNA Calculator](http://www.meadmakr.com/advanced-sna-calculator/). Both are good to use. The google doc helps you build your PPM off your YAN and has some tsp conversions that are VERY handy so it’s what I use. The Meadmakr requires you to know your desired YAN. If you want to calculate your YAN target on your own the math for it is on the whitepaper. 

The instructions are on the right hand side of the tool. Read them now.

The top calc is for splitting nutrients between Fermaid O, Fermaid K, and DAP. They are calculated in order, so if you only need a low nitrogen requirement only Fermaid O or K may be used by the calculator. The bottom calc is for TOSNA more or less. The difference between this and other calculators is that it directly tells you your PPM YAN amount, and you can add or reduce the addition based off opinion and fruit load. A melomel takes less nitrogen than a traditional.
 
On this note, one thing to think about in the instructions is Step 3. I use 50ppm offset for 1-2 lbs fruit per gallon and I halve the YAN needs if I have more fruit than that. Testing and experience will help you develop your own opinions. Once you have your gram additions you want to figure out how to split your SNA schedule. The best schedule is generally 3 additions at 24 hours, 48 hours and at the 1/3rd sugar break. The only nutrients that go in at the start are the rehydration nutrients, goferm PE or an equivalent. That nutrient is added in at 1.25X your yeast weight and you should be using 5-10g of yeast depending on your preferences and your ABV. 

If you have Goferm, and a correct target YAN PPM you will ferment quickly to completion without stalls, off flavors and a whole host of other issues. If you are struggling with consistent fermentation, this is where you want to start improving.

###Overview of a brew day
Get your yeast. This is where the brew day starts. It determines the gravity you start with and your final gravity. Do you want a sweet mead and your yeast has 14% tolerance? Use Meadcalc to find out how much sugar you need to add to get 16% potential, and you will have 2% residual. Start rehydrating this 2 hours or so before you want to pitch.

Get your water. You want spring water, and not distilled unless you intend to salt balance like it’s a beer. Very little research is done with mead in this respect. For a good rule of thumb, if you like the taste it’s good to use. You do not want anything with chlorine/chloramine in it. 

Get your honey. Raw and local is best but there are places for all types of honey. Lesser honeys are great for melomels and bochets. Light flavor honeys make for great traditionals. Blending two in a batch like a cranberry melomel bochet which is fermented dry and then backsweetened with meadowfoam can make for a very complex mead with a lot of depth and character. 

Get your fruit. Fresh fruit that you have frozen yourself is the best you can get, but there are many options. Puree is fine, store bought frozen fruit works great, fresh fruit added direct is very common. Campden tablets can stun yeast and microbes in a fruit addition to let your pitched yeast have less competition or you can trust your yeast to have enough of a leg up with rehydration or being a specific kill factor strain like 1116 that was designed to out compete even other brewing yeasts and inhibit their growth. A last option is to do a 140F hold on the fruit, but not boiling. This sterilizes with heat without damaging aromatics unduly. Putting your fruit in a bewers bag allows easy removal of fruit, reduces mead loss and makes racking far less of a challenge.

Get your herbs. In my opinion every single herb and flower should be put through a 140F hold in water for two hours to make a strong tea that is then used as the base for the must. Many flowers and herbs will impart vegetal flavors or too much tannin if left in the must for a long time, like in a long primary. Color can also be preserved much better from a tea base rather than just a straight addition in primary or secondary. 

Get your adjuncts. These are spices, peppers, and everything that doesn't contribute sugar. Some of these are hard to do right. Cocoa nibs and juniper are common infection vectors because of their difficulty to sanitize. A brief heat can work well or adding them later, rather than in primary can really help your odds. They also add nothing meaningful in primary and many yeast may be destructive on delicate flavors like vanilla and orange zest. Sometimes vodka tinctures work wonders on oddball ingredients.

Once you have everything together, scrub, rinse then sanitize all your equipment with starsan. Bleach reacts with DAP, and generally isn’t a useful tool for a brewer. Iodophor is a common sanitizer but it stains badly. Mix your must and prepare your ingredients as stated above. Your must should be heated or cooled until it is between room temperature and 80 degrees.  While this is happening you should have your yeast rehydrating in Goferm. There are no substitutes if you are stateside at the time of this writing for goferm rehydration nutrients. Rehydration nutrients are NOT the same as "nutrient", "energizer", or even other Fermaid Products. Rehydrate at your yeast's desired temperature and leave it until your rehydration is within 10 degrees Fahrenheit of your must. Some brewers prefer to attemper the yeast addition into the must in a staggered fashion. Your must is now complete. Add an air lock and wait for the ferment to begin. It is best practice to add no other nutrients at this point, and then to begin the staggered nutrient protocol of your choice after 24 hours.


###Overview of the fermentation

Every day, up to twice a day till the 1/3rd sugar break you should be aerating. This is commonly done with a drill stir and are commonly available at a home supply store. Aeration promotes strong cells walls and helps yeast ferment to completion without off flavors. This helps prevent stalls due to ABV. A drill stir and fermenting in a bucket is one of the easiest ways to do this, but there are other methods like O2 stones, shaking and so on. Each day take a hydro reading to get a feel for how they yeast is doing, and consider recording the data in a journal. This is easier in a 5 gallon pail and in smaller batches a refractometer really shines. Note that a refractometer requires a hydrometer to calibrate and charts must be used to correct SG readings from the presence of alcohol. 

Nutrients should be done at 24 hours, 48 hours and the 1/3rd sugar break. Write down how much you are adding and your target YAN, determined in the YAN Calcs section. Generally you want to splint your total nutrient addition into even thirds and add equal amounts each time of each nutrient. After 2-4 weeks you should remove any fruit or solids in the mead, they quickly become an infection vector. At 4-8 weeks the mead should be clearing up and the lees dropping. Once this is done, rack. Being overzealous in racking results in oxidation and gains nothing. Only at larger volumes than homebrew will leaving the mead on the lees be an issue for 8 weeks. After the mead is reasonably clear (or earlier) sample the mead to make sure you don’t need to backsweeten, add in more adjuncts, or tweak the tannin/acid balance to get a good mead. Very often a small amount of sugar and acid can dramatically change the way a honey or fruit presents. 

###Secondary 

Secondary refers to the process that follows "primary" fermentation, typically involving racking into a new vessel (typically glass) to get the mead off the gross lees once fermentation has completed. While it is possible to involve a "secondary fermentation" at this stage (such as using brettanomyces), it most commonly refers to the stage where backsweetening, aging, clearing, and other adjustments of the final mead occurs.

The goal for this stage is clarity, maturation, and balancing. Mead can be damaged by improper storage and handling at this phase (see [bulk aging](/process/aging#bulk_aging) for more details). Use best practices will ensure the longest lifespan and highest flavor potential for your mead.

###When to stagger sugar
I stagger sugar whenever I want to push the limit of what a yeast is capable of. The only time it makes sense to do this, is when you can’t pick a yeast strain that fits your needs otherwise at that yeast’s stated ABV. Two common yeasts to do this with are 1118 and WLP-099 having an 18% and 25% ABV tolerance respectively. WLP-099 is less predictable and generally requires more care with temperature and pH and ferments slower as a whole. Staggered sugars work well with any champagne yeast as well. Other instances could be when you want to get a specific ester out of a yeast, but want an ABV that it doesn't generally go to. Staggering sugar pushes far past an yeasts intended ABV when combined with modern nutrition and a rapid ferment. It is possible to go 4% or more past stated tolerances this way. The general idea behind staggered sugar is to start with a third of your honey in the batch and then add more every time you get to ~1.050 SG. I generally split my sugar additions into 5ths, 24h / 48h / 1/3rd sugar as per normal, and then Fermaid O/K on the second two sugar additions to hit my total YAN target. DAP cannot be consumed by yeast past 10% ABV, and when pushing the envelope you need to make sure additions of it are front loaded.

###Stabilization, do’s and dont’s 
You have a few options. Heat, filter, chemicals and ABV are the 4 most common ones, with ABV being the simplest and chemical stabilization being extremely common when compared to sterile filtration and heat. See these two links for stabilization on the wiki [Stabilization-Basics](/faq/stabilization_and_backsweetening) and [Stabilization-The Gritty Details](https://www.reddit.com//process/stabilization)


For heat, make sure you are at temp long enough. Bottle bombs can be devastating. For sterile filters, make sure your sugar source if you use one post filtering will not add any bugs. Sterile filters need to filter down to .35 micron and may affect taste or mouthfeel. Raw honey added post filter that hasn’t reached pasteurization temperatures is a bad idea, especially at lower ABVs. As for chemicals, make sure to use potassium sorbate and sulfite together and do not use sodium based stabilizers as they impart a salty taste. Also, they are meant to be used when the ferment is temporarily halted, either by running out of sugar, or after a lengthy cold crash that stops current activity. Adding them mid ferment may or may not halt the fermentation. ABV stabilization is a GREAT way to keep it simple. If you are going this route, make sure your mead finishes just a little sweet and really let it sit a while at the warmest it will be in storage. Then backsweeten and make sure the mead does not ferment. A hydrometer is the way to test this.

Again, bottle bombs are not fun. Do your reading on stabilization!

A final option is nonfermentables. Let’s say you don’t care for any of the methods above. Xylitol is a natural sweetener that doesn’t have a chemical flavor like Splenda and the like and is a sugar alcohol. It’s about 2/3rds as sweet as real sugar (Warning:  Xylitol is **extremely** toxic to dogs.  If you choose to use it, take care no dogs have opportunity to consume your mead and warn anyone you gift a bottle to). Erythritol is another option, I have not personally tried it but it looks very cost effective and is supposed to be easier on the gut than other sugar alcohols. Lactose can add body as well as maltodextrin. Both can be fermented by some more interesting bacteria and infections and even some yeasts. Never bottle straight away after adding sugars, no matter the way you are intending to prevent refermentation. More reading on backsweetening is available here [Backsweetening](/process/back_sweeten)


###Acid tannin balance

This is a very important step, especially when making your own recipes. In a removed tasting sample, try to add small amounts of cocktail bitters, table sugar and lemon juice. The balance between the three is like a stool with three legs. It can be shorter or taller, but if one is out of whack it doesn't sit right. This can quickly tell you if your mead would fare better with a different acid/sugar/tannin balance. When you are ready to scale it to your batch oak or wine tannin powders are good adjuncts to enhance bitterness. On future batches, higher ABV can increase bitterness. Citrus pith can add bitterness as well as many other adjuncts. For acid or tartness, a variety of fruits could be used in secondary, but sometimes just a little acid available at any brewing store can make flavors pop. Options are citric, tartaric and malic acid. Each lends a little different flavor and I keep all 3 on hand.