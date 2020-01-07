# aws-nodejs-layer
 Library to create nodejs Lambda functions with layers.

This CDK Construct creates a layer with all the node_modules bundled in it.
This makes incremental packaging of the lambda function quicker & smaller.

A Lambda created with this construct is also editable in the console (if one needs that for debugging purposes).
