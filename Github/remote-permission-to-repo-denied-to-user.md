# remote: Permission to "REPO" denied to "USER"

If you try to push to a new user while an existing global user is registered, the following error occurs.
'''
remote: Permission to "REPO" denied to "USER".
fatal: unable to access "REPO_URL": The requested URL returned error: 403
'''

Solution:
1. Run the Keychain Access.app.
2. Search for github.com.
3. Change the USER value corresponding to the account among the attributes.

