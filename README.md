# githook_pre-receive_compareVersions

A githook which checks files in a given directory for both old and new revisions. It compares only differences in filelists and if there are two or more files with the same prefix it throws an error.
