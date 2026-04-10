# Present issues

I suspect leaving the model to figure out the index of the tokens, words and replacements will lead to indexing issues when rendering the diff changelogs in the frontend. This has to be addressed.
A PR from Devin mentioned that having useCallback and analyze send new API requests on style input refreshes. Worth taking a look
