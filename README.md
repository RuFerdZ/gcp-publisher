# Google Cloud Pub/Sub Publisher

Learn more about publishing and receiving messages with Google Cloud Pub/Sub [here](https://cloud.google.com/pubsub/docs/publish-receive-messages-client-library).

This is a Python script that publishes messages to a Google Cloud Pub/Sub topic. It uses the `google-cloud-pubsub` library to interact with Google Cloud's Pub/Sub service.

## Prerequisites

1. **Google Cloud Account**: You need a Google Cloud account to use Pub/Sub services.
2. **Google Cloud Project**: Ensure you have a project created on Google Cloud. In this example, the project ID is `myfirstapp-72240`.
3. **Service Account and Credentials**: 
    - Create a service account in your Google Cloud project and download the associated JSON key file.
    - Set the environment variable `GOOGLE_APPLICATION_CREDENTIALS` to the path of your service account's key file.
4. **Python and Required Packages**: You should have Python installed, along with the `google-cloud-pubsub` library.
