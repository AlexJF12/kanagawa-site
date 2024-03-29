## What is Kanagawa?

Kanagawa is a service that provides political campaigns with an aggregated report and raw public data about their district, voting history, and voters. 

Submit a request [here](https://www.kanagawa.io/contact) to get started:

[https://www.kanagawa.io/contact](https://www.kanagawa.io/contact)

## First, what will this cost?

For the 2022 cycle - nothing! It's being offered free since it is still a work in progress. All I ask is for some constructive criticism.

That being said, if there is custom work beyond the report you'd like to have done, we can figure something out.

## Who would benefit from this data and report?

If you are interested in running for office, this is a good place to start.

And if you are currently running for a local office, you may not have the resources to hire a data person, much less a team. Don't sweat it! You can use the information provided in this report to help target your GOTV, persuasion, and fundraising efforts.

## What files are included in the report?

* The Voter File, as provided by the State of Florida
* Predictions, per individual, on their likelihood to vote and their likelihood to be a Democrat
* The FEC Donor File of individuals who donated to Federal campaigns/PACs from your district's general area
* An interactive map of the 2020 Election results at the precinct level
* Google Ads, who paid for them, amount paid, number of impressions, and more of ads placed on Google for the District's area
* An aggregated report showing various counts and sums of voters and donors in different regions

## What is in the Voter File?

The voter file is actually two files. The first file provides information on each registered voter in the state of Florida. It includes their name, address, party registration and a few other fields. The second file contains each voter's voting history, including elections they were elgible to vote in, if they voted, and by witch method (in person, mail, etc.).

I have supplemented the donor file with a voter_likelihood and democrat_likelihood, my predictions for their propensity to vote in the upcoming election and to be a democrat.

## What is in the FEC Donor file?

Every donation made to a federal political campaign or PAC is reported to the FEC and made public (eventually). The name, organization, occupation and zip code of the individual donating is included. This report finds everyone who has made a federal political donation in a zip code that overlaps with the district in question. Donations made to state/local political campaigns are not reported to the FEC and are not included in this report, yet.

## What predictions are you making?

Right now, there are two new values I have created to go with the Voter File (provided by the State of Florida).

1. Likelihood to Vote: This value, between 0 and 1, is the rate at which the individual has voted in all elections they have been eligible for, according to the voter file. An individual who has been eligible to vote in 3 elections (primary, general, federal, state, local) and cast a ballot in 2 of them would have a value of .67. An individual who has been eligible to vote in 22 elections and voted in 7 of them would have a value of .32.
2. Likelihood to be a Democrat: This value, again between 0 and 1, is the chance that this person would support a Democratic candidate (1 being certainly a democrat). This value is created on a combination of facts, including party registration, age, gender, ethnicity, party registration of members of their household and others.

These predictions will be refined over time, and others will be added.

## What types of districts are available to purchase?

County, School Commissioner, State House, State Senate, US House, and US Senate. If there are other districts you are curious about, feel free to inquire.

## Why only Florida?

I have previous political work experience in Florida, so I figured I'd start there.

## Do you have this report for districts in other states?

Not at this moment, but feel free to reach out and I can see what's possible.

## What side of the politcal divide do you work with?

The Great Blue Wave logo should tip you off, but I work with candidates who align with progressive values. Saying that, I understand that many local races are technically non-partisan. In addition, I recognise that many local races are decided in the primary. If you want to win, somethimes you need to register with a party in name only. Feel free to reach out.

## Can I see a sample report?

Yep! I've created a sample based on Florida's 22nd State House District. The PDF file is based on real voter and donor data, but only on a sample of 1000 voters. In addition, I've modified the CSV files of the voter file and donor file with fake names and other information, but the columns are the same.

<a href="https://github.com/AlexJF12/kanagawa-site/blob/6d5b2966812ca3f3b57deb27727bebe99eb76c7c/assets/sample_kanagawa_output_fl_house_22.zip" download>Download Sample</a>

## How do I get in touch with you?

[Fill out this form](https://www.kanagawa.io/contact) with your name, your email, the disctrict you are interseted in and anything else you'd like to tell me.

[https://www.kanagawa.io/contact](https://www.kanagawa.io/contact)

## Why is this called Kanagawa?

[The Great Wave off Kanagawa](https://en.wikipedia.org/wiki/The_Great_Wave_off_Kanagawa) is a famous woodblock print by Japanese artist Hokusai. Woodblock printing requires meticulous work to shape the face of the wood into a piece of art, but can then be used to print its image over and over. In a similar vein, the program to generate this report requires meticulous coding work, but can be used repeatedly to create the finished product.

🌊
