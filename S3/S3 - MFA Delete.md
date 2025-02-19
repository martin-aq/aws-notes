* **MFA (Multi-Factor Auth) -** force users to generate a code on a device (e.g. Google Auth or a MFA Hardware Device) before doing important operations on S3.
* MFA will be required to:
	* Permanently delete an object version
	* Suspend Versioning on the bucket
* MFA won't be required to:
	* Enable Versioning
	* List deleted versions
* To use MFA Delete, **Versioning must be enabled** on the bucket
* **Only the bucket owner (root account) can enable/disable MFA delete**


## Tags
#S3 #SAA-C03