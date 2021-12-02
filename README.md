## Welcome!

This is the GitHub repository for the OHBM Open Science Room (OSR).

This repository hosts the code for [the current OSR2022 website](https://ohbm.github.io/osr2022).

Below we provide basic info and links to more information. 

### Who are we?

We are part of the [Open Science Special Interest Group](https://ossig.netlify.com/) (OSSIG) of the [Organization for Human Brain Mapping](https://www.humanbrainmapping.org/i4a/pages/index.cfm?pageid=3267&pageid=1).

### What are we doing?

We are organising, among other events, the Open Science Room at the <a href="https://www.humanbrainmapping.org/i4a/pages/index.cfm?pageid=4114" target="_blank">hybrid 2022 meeting of the OHBM</a>.

### Get involved

All information is available on [our website](https://ohbm.github.io/osr2022).

### Contact us

Feel free to [reach out to us](https://ohbm.github.io/osr2021/contact/)!


---

### Credit
The [OSR website](https://ohbm.github.io/osr2022) was built using the [Beautiful Jekyll](https://deanattali.com/beautiful-jekyll/) theme by [Dean Attali](https://deanattali.com/).


#### Instructions for building website (these must be run prior to uploading onto GH)
Check the speaker/volunteer CSV files are in place (in _data/speakers, _data/volunteers)
Wipe the built directories if they already exist, and re-build: 
`rm -r _speakers _volunteers; bundle exec jekyll pagemaster speakers volunteers`
Commit the new directories and push the site. This must be done every time the CSV files are changed. 
