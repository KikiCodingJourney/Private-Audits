# Audit Process

## Q&A questions to improve the overall experience through the audit.
 1. On what chains are the smart contracts going to be deployed?
 2. Which ERC20 tokens do you expect will interact with the smart contracts?
 3. Which ERC721 tokens do you expect to interact with the smart contracts?
 4. Which ERC777 tokens do you expect will interact with the smart contracts?
 5. Are there any FEE-ON-TRANSFER tokens interacting with the smart contracts?
 6. Are there any REBASING tokens interacting with the smart contracts?
 7. If the smart contracts integrate with admin roles, do you consider the owners of this roles **TRUSTED** authorities?
 8. List any known issues which shouldn't be accounted by the auditor.

## Additional technical questions.

 1. What's the clear scope of the audit in terms of number **SLOC**?
 2. Is the code documentation still considered accurate and correct till this moment?
 3. Are there any other details which may be helpful through the audit review?

**Fixed pay and time duration of the private audit would be discussed with the project based on the answers given.**

## Recommendation fix review.

After the private audit has ended, the project will receive the results for the audit. The project has a week to apply fixes on the issues found.
Each issue in the report has a recommended fix written which is already traced and secured, the project has the right to apply a fix on their own. 
Which will be further reviewed by me, without additional charges, to verify that your fixes are correct and the code is secured.

**Additional notes regarding the fix reviews:**
- for any questions or clarifications on the vulnerabilities/recommendations in the report, you can reach out to me on the intended channel of communication.
- changes to be reviewed should not include anything else other than fixes for the reported issues, so no big refactorings, new features or architectural changes.
- in the case that fixes are too difficult to implement or more than one iteration of reviews is needed then this is a special case that can be discussed independently of this review.

## Important Disclaimer

- **A smart contract security review is a process of assessing the code and implementation of a smart contract to identify potential vulnerabilities and weaknesses that could be exploited by malicious actors.**
- **This is a time, resource and expertise bound effort where I try to find as many vulnerabilities as possible. Therefore I can not guarantee a full security after the audit!**
