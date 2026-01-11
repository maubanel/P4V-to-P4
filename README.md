# P4V-to-P4


* <button>Get Latest</button> button: `p4 sync`
*  <button>Submit</button> button no changelist: `p4 submit -d "Your changelist description"`
* Changelist menu list for user: ` p4 changelists -s pending -u username`
* Changelist menu list for workspace: `p4 changelists -s pending -c workspace_name` 
* Change to specific changelist: `p4 submit -c 12345`
* Preview the submission: `p4 submit -n`
* Preview if there is offline work ready to reconcile: `p4 reconcile -n`
* Reconcile offline work: `p4 reconcile`
* File open for edit (list of files in default changelist): `p4 opened`
