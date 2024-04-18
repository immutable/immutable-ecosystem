
<p align="center">
  <a href="https://www.immutable.com">
    <img src="https://cdn.dribbble.com/users/1299339/screenshots/7133657/media/837237d447d36581ebd59ec36d30daea.gif" width="280"/>
  </a>

  <h2 align="center">Immutable Ecosystem</h3>

  <p align="center">
    Immutable's Partner Ecosystem Registration.
    <br />
    <a href="https://www.immutable.com/ecosystem"><strong>Explore the partner ecosystem »</strong></a>
    <br />
  </p>
</p>

# Immutable Partner Ecosystem

🌲 Immutable Ecosystem is a partner repository for registering, sharing and updating partner details. All of the partners in the ecosystem are specified in [TOML](https://github.com/toml-lang/toml) configuration files.

This repository is not complete, and hopefully it never is as there are new partners joining everyday.

Immutable is a global leader in gaming on a mission to bring digital ownership to every player by making it safe and easy to build great web3 games.

## How to Sign Up

There's a couple of ways you can sign up as an Immutable ecosystem partner

### Option 1: Opening a Pull Request

You can make any .toml file for a partner under the `/ecosystem` directory or edit an existing one to  improve information about a partner.

You can fork this repository and open a PR from the forked repo to this repo.

#### Data Format

An example configuration file for the Labrys partner looks like this:

```toml
# Partner Level Information
title = "Labrys"
website="https://labrys.io/"

# Partner company details
registered_company_name = ""
registered_company_address = ""
company_registration_number = ""
company_representative_name = ""
company_representative_email = ""
company_poc_name = ""
company_poc_email = ""

# Partner Directory details
logo="https://labrys.io/wp-content/uploads/2024/03/logo-1.svg"
brand_hex="#00FFA7"
description="Labrys is the largest web3 consulting and development agency in Australia. We work with clients to plan, design, build and deploy custom web3 solutions"
discord=""
twitter="https://twitter.com/Labrys_io"
region_focus=[APAC/NA/EMEA]
service_category= [Web3 Development]

# Partner service details
detailed_overview_of_services=""
strengths=""
weaknesses=""
projects=""
price_range=""
get_in_touch_process=""
get_in_touch_email=""
get_in_touch_telegram=""
get_in_touch_phone=""
get_in_touch_calendly=""
other_details=""
```

By specifying the data as evolving config files in git, we benefit from a long term, auditable database that is both human and machine readable.

### Option 2: Complete the Ecosystem Submission form

If you are not a developer or you find making a commit too difficult, you can use an input form

You can [visit the form here](https://immutable.mfs.gg/NqcIBa7?radio_939=I%27d%20like%20to%20discuss%20a%20partnership%20opportunity%20with%20Immutable%C2%A0), fill it, submit it and we'll take care of the rest :)

## How to share information that you don't want publicaly accessible

Please note in your submission "Provided on request" and we'll reach out for those details when we're adding you to our Partner ecosystem


## What information to share (Detailed Guide)

There are three types of details we are asking you to share:

1. Partner company details - these are the details of your operating entity
2. Partner Directory details - these are the details you want shared in our [Partner Directory](https://www.immutable.com/partner-directory)
3. Partner service details - these are the details relating to what services you offer and customer references

To make things easier, we've made the following roadmap for you to follow depending on which of the above 3 types of contributions you're trying to make. 

### Detail 1: Partner company details
| Field | Description | Example |
| --- | --- | --- |
|registered_company_name | Name company is registered under | Labrys Pty Ltd |
|registered_company_address|Address company is registered at| 14 Anonymouse St, Windsor QLD Australia |
|company_registration_number|Company EIN/ABN/VAT/business registration number| ABN 123 345 456 |
|company_representative_name|Name of company representative signing agreement| Mr CEO |
|company_representative_email|Email of company representative signing agreement| ceo@labrys.com |
|(Optional)company_poc_name|If different to signer, name of company representative as poc| Mr POC |
|(Optional)company_poc_email|If different to signer, Email of company representative as poc| poc@labrys.com |

### Detail 2: Partner Directory details
# Partner Directory details
| Field | Description | Example |
| --- | --- | --- |
|logo|PNG file preferred that goes well against white background|https://labrys.io/wp-content/uploads/2024/03/logo-1.svg|
|brand_hex|(Optional) Brand Hex colour #000000|#000000|
|description|Short description of company <160 characters|Labrys is the largest web3 consulting and development agency in Australia. We work with clients to plan, design, build and deploy custom web3 solutions|
|discord|Discord contact||
|twitter|Twitter contact|https://twitter.com/Labrys_io|
|region_focus|Regional focus for services or audience e.g. [APAC/Japan/Korea/NA/LA/EMEA/Global]|[NA/APAC/EMEA]|
|service_category|Preferred categories for searching within Partner Directory e.g. [Developer/Web2 development/Game distribution/Community Engagement/Solidity auditors/Marketing agencies/Game development & design/Web3 Infrastructure]|Web 3 Developer|

### Detail 2: Partner service details
| Field | Description | Example |
| --- | --- | --- |
|detailed_overview_of_services=""
|strengths=""
|weaknesses=""
|projects|Games integrated with Immutable
Other games
Non-gaming projects
|price_range|What is your price range. Example standard rate card for reference, noting you’ll negotiate with individual projects| USD$50-$75 per hour|
|get_in_touch_process|Process for how you want Immutable to get in touch with referrals|Example: Happy for you to get in touch with any of the below. Email/TG introductions are always good, but please don’t hesitate to call if you have any pressing questions. Else also happy if you book a meeting with me directly any time.|
|get_in_touch_email|Email address for Immutable referrals|referrals@labrys.com|
|get_in_touch_telegram|Telegram handle for Immutable referrals|@TGhandle|
|get_in_touch_phone|Phone number for Immutable referrals|+1 123 345 546|
|get_in_touch_calendly|Calendly URL link for scheduling a meeting|http://calendly/link123|
|other_details|Anything else our team should know about your company or your services||

## The process from here

Once you've submitted your PR our team will review your submission. We qualify partners based on the following prioritisation criteria:
1. Requested services from Immutable game customers
2. Requested services from Immutable internal teams
3. Active common game customers (i.e. customer is actively working with Partner and Immutable)
4. Interested common game customers (i.e. customer is considering to work with Partner and Immutable)
5. Active game customers (i.e. game developer is working with Partner)
6. Votes on PR
7. Date submission provided

Unfortunately, we can't provide an estimate of when your submission will be reviewed but rest assured, our team is working through submissions as quickly as possible. If any of the above criteria changes after you've submitted (i.e. you secure a customer who already is building on Immutable) please let us know via the comments on your PR.

Thank you for reading the partner sign-up guide! ❤️
