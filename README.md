see https://0xpolygonid.github.io/tutorials/verifier/verification-library/verifier-set-up/

Note: Relies on credentials issued by demo Issuer: https://issuer-demo.polygonid.me/

# Run a Verifier
- A Verifier is made of a Server and a Client.

The Server generates the ZK Request according to the requirements of the platform. There are two types of authentication:

- Basic Auth: For example, a platform that issues Credentials must authenticate users by their identifiers before sharing Credentials with them.

- Query-based Auth: For example, a platform that gives access only to those users that are over 18 years of age.

## Goal
Client needs to embed a QR code that displays the zk request generated by the Server

After scanning the zk request, the user will generate a proof based on that request locally on their wallet.