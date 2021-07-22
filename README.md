# A/B Testing
This project consist of analysing the company ad campaign performance using A/B testing

## Project overview
An advertising company is running an online ad for a client with the intention of increasing brand awareness. Post showing the ad to online users the advertising  company provides an additional service called Brand Impact Optimiser (BIO), a lightweight questionnaire, served with every campaign to determine the impact of the creative, the ad they design, on various upper funnel metrics, including memorability and brand sentiment.

The main objective of this project is to test if the ads that the advertising company runs resulted in a significant lift in brand awareness.

## Project objective

The task to complete is to design a reliable hypothesis testing algorithm for the BIO service and to determine whether a recent advertising campaign resulted in a significant lift in brand awareness.

## Dataset

The BIO data for this project is a “Yes” and “No” response of online users to the following
question

    Q: Do you know the brand ?
        O Yes
        O No

### Dataset columns

    ● auction_id: the unique id of the online user who has been presented the BIO. In standard terminologies this is called an impression id. The user may see the BIO questionnaire but choose not to respond. In that
    case both the yes and no columns are zero.
    ● experiment: which group the user belongs to - control or exposed.
    ● date: the date in YYYY-MM-DD format
    ● hour: the hour of the day in HH format.
    ● device_make: the name of the type of device the user has e.g.Samsung
    ● platform_os: the id of the OS the user has.
    ● browser: the name of the browser the user uses to see the BIO
    questionnaire.

## Methods implemented
    ● Classical A/B testing
    ● Sequential A/B testing
    ● Machine learning

## Project structure

