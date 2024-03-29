# Engineering Support

Tools and processes for managing bugs, problems and blockers involving the RFCx platforms.

## Tools

[Create a new issue](https://github.com/rfcx/engineering-support/issues/new/choose).

Issues are triaged and managed in the [Engineering Support GitHub project](https://github.com/orgs/rfcx/projects/10).

New issues are created by Engineering in the current repo by default, but can be transferred to a product-specific repo after triaging.

## Support Options

### Slack channel

If you have access to Slack then posting issues in the #eng-support channel will get the fastest response. Engineering will prioritise issues affecting our internal team.

### HelpScout

External users can send a message to a support agent via support.rfcx.org or they can email support@rfcx.org. Both result in a conversation thread in HelpScout.


## Support Process

```mermaid
flowchart TB;
  input1[External user reports issue to support at rfcx.org or HelpScout]-->p1[Engineering logs issue in GitHub board];
  input2[Internal user reports issue on Slack #eng-support]-->p1;
  p1-->p2[Engineering triages and assigns a resolution date for business critical issues];
  p2-->p3[Issue resolved and user informed via HelpScout or #eng-support channel];
  p3-->p4[Issue closed]
```
