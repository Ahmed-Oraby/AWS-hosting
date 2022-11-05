# Create Elastic BeanStack Environment to host back-end

## Steps

-   use eb CLI to create eb environment using the following commands:

    1. eb init to initalize the app.
    2. eb create --sample udagram-api-dev to create environment.
    3. eb use udagram-api-dev to use the environment.
    4. eb setenv to set environment variables.
    5. eb deploy to deploy application.

-   when using CircleCi, all the above will be automated using the pipeline
