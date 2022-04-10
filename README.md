# OpenWelfare:
Services Australia Operational Blueprint Freedom project

## Master problem: 
Our welfare system [hides half of how it works](https://docs.google.com/spreadsheets/d/1a5iNs4PwOGUbDzLuxudHfv1HWCprqAee1GzQZ0e-dLE/edit#gid=0) from the needy public.

###Sub problems:

1. In the [existing public offering](https://operational.servicesaustralia.gov.au), even finding out that the master problem exists is beyond the capacity of a human, a click per topic to process.

2. If you follow the instructions provided to get you access to the article, you guarantee that others beside yourself cannot access the article as all documents on the FOI disclosure log are only "[available upon request](https://www.servicesaustralia.gov.au/freedom-information-disclosure-log?context=1)". This has an easy solution once you know it - use [Right To Know](http://righttoknow.org.au)

3. Given that we now know there are literally thousands of pages that are blocked, it is hard to keep track of what has been released and what has not, and what is hidden behind a 'request wall'.

##Prior attempted solutions:

1. Just Ask The Government For All The Documents: Result - [No, too much work](https://www.righttoknow.org.au/request/all_documents_marked_potentially).

2. Tell Us How You Decide What To Block: Result - [No, what?](https://www.righttoknow.org.au/request/decision_making_criteria_for_pot#incoming-12159)

3. If Giving Us All The Documents is Too Hard, Can we Just Have All The Debt Ones?: Result - [No, uh, hangon, $700 please to do our job](https://www.righttoknow.org.au/request/operational_information_debts#outgoing-11873).

4. Can I have them one at a time? Result: [mostly yes, at begrudgingly no cost, with some arguing](https://www.righttoknow.org.au/search/posty%20requested_from:services_australia/all).

## New proposed solution:

Take what we know works (requesting them one or two at a time) and have a lot of completely disconnected, unrelated people who care about their respective topics request them.

## How?

With our ["Blocked or Not" search query spreadsheet](https://docs.google.com/spreadsheets/d/1a5iNs4PwOGUbDzLuxudHfv1HWCprqAee1GzQZ0e-dLE/edit#gid=0) 3 step process.

1. Find a coloured red blocked article on [the spreadsheet](https://docs.google.com/spreadsheets/d/1a5iNs4PwOGUbDzLuxudHfv1HWCprqAee1GzQZ0e-dLE/edit#gid=0)

2. Copy the Article Title from the Sheet (it includes the article number), Register an account and write a request on [Right To Know](http://righttoknow.org.au/) as [10 people already have](https://docs.google.com/spreadsheets/d/1a5iNs4PwOGUbDzLuxudHfv1HWCprqAee1GzQZ0e-dLE/edit#gid=871559379).

3. Submit your request. Congratulations! The Federal government now have a legal obligation to respond to your request in 30 days!

***It's that easy!***

And bingo, the very next day, that Article won't be red anymore, and you will get email updates about your request!

Whether you actually succeed, fail or have partial success (eg redacted documents) you will have furthered our knowledge of how this behemoth of a system works.

##How does this technically work?

The last [Operational Blueprint](https://operational.servicesaustralia.gov.au) raw html is saved nightly to "Current" folder, the previous nights saved "Previous" and all 'previous' versions copied into the folder 'archive' for easier retrieval of deleted content.

Plaintext versions are created in subfolders with -plaintext on them.

A program is run against the data to generate the required tests - eg, is the article blocked or not, when was it last updated, has anyone requested it before on RTK, on the disclosure log etc.

Those tests are put in The Operational Blueprint Freedom Report master report tab separated values file:
OpenWelfare-OperationalBlueprintFreedomReport.tsv


## So, why, apart from the problem above did you do this?:

As Centrelink/Services Australia says on it's Information Publication Scheme (IPS) Agency Plan says:

https://www.servicesaustralia.gov.au/information-publication-scheme-ips-agency-plan?context=1

"The Operational Blueprint explains how we deliver services. It also holds reference material to support staff delivering those services. It contains all service delivery operating procedures in simple, clear language that can be accessed and understood by staff, customers and stakeholders. It allows for greater transparency and consistency when making service delivery decisions.

IPS documents are downloadable from the Operational Blueprint page or available upon request as follows:

by emailing freedomofinformation@humanservices.gov.au
by mailing:
Freedom of Information
PO Box 7820
Canberra Mail Centre, ACT 2610
The ELFOI Branch continually reviews the Office of the Australian Information Commissioner's Guidelines to determine whether documents we hold fall within the definition of operational documents."

This is required by law, due to the 1983 Freedom of Information Act - as explained by the Information Commissioner:
https://www.oaic.gov.au/freedom-of-information/accessing-agency-information/information-publication-scheme

"The Information Publication Scheme (IPS) makes agencies, with some exceptions, publish on their website certain information they hold, as well as an information publication plan. The IPS encourages agencies to be open and transparent, and consider publishing information that they aren’t obliged to publish.

The published information must be accurate, up to date and complete. You may find it on an agency’s website by looking for the IPS icon or searching for ‘freedom of information’ or ’IPS’.

The IPS doesn’t require an agency to publish information exempt from disclosure under the Freedom of Information Act 1982 (FOI Act) or is prohibited from being released under other laws."

That last bit is key - If Centrelink thinks you shouldn't be able to see how a process works (right or wrong), it is put behind a page that says:

"The guideline you have requested is potentially FOI exempt.

You have a right to apply for the document through FOI legislation.

You can request a copy from the department's Information Publication Scheme by:

sending an email to freedomofinformation@humanservices.gov.au
or writing to us at:
Freedom of Information
FOI and Information Release Branch
PO Box 7820
Canberra Mail Centre ACT 2610"

This project started to initially answer the question:

"How much of the operational information is blocked behind this FOI "Block"?"

I find it hard to believe that literally half of all procedures should be blocked. Every Australian will interact with Services Australia, why is over half of how the organisation works secret?

How does this meet Service Australias stated IPS goals?

I have had success in releasing 5x completely pages personally, more to a partial success. some released in months scale, some years.

After seeing exactly how many blocked pages there were, I had the realisation that one person cannot complete this task, this requires community.

It appears the only way that this information will be more readily released is to either bring to light the fact it is not, or request each page individually.

This will help target success.

The design of the Operational Blueprint is such is that it should always have the most up to date information.

This is useful, for most purposes - but does not reflect the natural order of things in which - things change.

There is no ability to:

track changes to the way centrelink operates - it assumes we live in the perpetual now.
know of updates to areas that are of concern to you or others you care about
know of new instructions
know when old instructions are updated
know what of the instructions is updated
know when old instructions are removed
know when articles are blocked from public view (put behind foi wall)
know when articles are released to public view (removed from foi wall)
In general - provide more transparency than is available by default

The people responsible for keeping the register up to date are Service Australia's National Managers for each area (see IPS link above).

According to Services Australia's Organisation chart page - there are currently 139 of them.
https://www.servicesaustralia.gov.au/organisational-structure?context=1

apsjobs.gov.au has previously advertised for National Managers - the most recent one is in the SES Band 1 pay. (notably I cannot link as apsjobs.gov.au links to an external site and specifically removes the National Manager role when salary searching) - I have this information from the candidate pack from the external recruiter that I had to hand over an email for.
archive.org copy here: https://web.archive.org/web/20220312052220/https://executiveintelligencegroup.com.au/wp-content/uploads/2022/02/804-NM-ICT-Digital-Data-B1-Services-Australia-Candidate-Information.pdf

transparency.gov.au advises that SES Band 1 are paid between $167,600 and $216,000 per annum at Services Australia in 2020-21
https://www.transparency.gov.au/find-data#MWI4LDFhd3BwMCwxYjgsMWF3cG96LDFiOCwxYXdwb3ksMWI4LDE5bjk1LDFiOCwxOW45NCwxYjgsMTE3ZnZlLDFiOCwxMTdmdmQsMWI4LDExN2Z2YywxYjgsMTE3ZnZiLDFiOCwxMTdmdmEsMWI4LDExN2Z2OSwxYjgsMTlrMHo0LDFiOCwtMmFleDUwJDU5JGZlOGYxOWNkLThmZjEtNTY1Ny04OGIxLTEyYTBjMjVjNDkyYV9kODRkNWIzMC0wNDgyLTQ1ZmItYTIxMC0wNjgwNDBlYzRkYWNfZnkyMFNjaGVtYV9TZXJ2aWNlcyBBdXN0cmFsaWFfMjAyMC0yMV8yMDIwLzIxJGNvbHVtbiQlNUIlN0IlMjJSYW5nZSUyMiUzQSUyMk1heGltdW0lMjBTYWxhcnklMjIlN0QlNUQkMSRjYXRlZ29yeSQwJDAkZmFsc2U

So this will help hold accountable at minimum between $23.2964 and $30.024 million dollars at least, as well as the publics right to know, in a prompt manner.

I also hope that by bringing to light these facts we can either together celebrate the Freedom Report going up, or commiserate it going down.

If you've got this far, you may wish to support the project - please follow [@Open_Welfare](http://twitter.com/open_welfare) for updates and DM if you think you can help.
