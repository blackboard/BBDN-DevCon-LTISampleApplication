# BBDN-DevCon-LTISampleApplication

The example shows how to build a simple LTI Tool Provider as a building block in Learn.

This provides a means of creating or porting existing course, user, system tools, etc. into LTI Providers so they can be used in Ultra courses.

To install & configure:

1.  Build this application and install the B2.
2.  Define a key and secret in the B2 settings.
3.  Add an LTI provider domain for the same url as the server where you are running this.
4.  Create LTI links or placements in your courses using the same key & secret.  The LTI url will be <bb home>/webapps/xyz-LTISampleApplication-BBLEARN/app/launch.

To extend this example:

Add to the Launch Controller hooks to direct to the various functions based on the action code.  Likely it makes sense to implemnt this functionality as a variety of services & additional views.

You will also want to add processing to ensure the correct user & role can use this tool.

