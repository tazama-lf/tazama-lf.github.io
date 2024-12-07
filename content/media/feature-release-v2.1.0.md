![Tazama v2.1.0 Feature Release Banner](/image/feature-release-v2.1.0-banner.png)
# Tazama v2.1.0: Feature Release

December 6, 2024

Today, we are delighted to announce the release of Tazama v2.1.0, a feature update designed to enhance our open-source transaction monitoring system. This new version introduces some much sought-after features that we have introduced in response to customer demand.

We are very excited to bring you this update, and we can’t wait to see what you will do with it!

## Key Enhancements in Tazama v2.1.0:

- **Condition Management**: One of our most requested features has been the ability for a Tazama operator to block specific entities or accounts from transacting on their networks for compliance, operational or safety reasons. Blocking functionality will be rolled out in this release and operators will now have the ability to block transactions (all types, or only specific ones) to or from an entity (including all their accounts) or just a single account. An operator will also have the ability to override blocking conditions for a limited time in response to operational needs.

- **Securing our APIs**: Tazama has, up to now, relied on the perimeter security provided by a cloud provider or a private network to prevent unauthorised access to its APIs. From this release onwards, Tazama introduces [KeyCloak](https://www.keycloak.org/), an open-source product hosted in the Cloud Native Computing Foundation, part of The Linux Foundation, to handle authentication and authorisation of Tazama API users and service requests.

- **Multi-currency support**: The Tazama Transaction Monitoring Service API has been extended to now also include the additional attributes that would allow for the evaluation of transactions in multiple currencies to meet the needs of a cross-border operator.

These features above were delivered in collaboration with **Sybrin**.

- **Improved Egress Integration**: Real-time transaction monitoring is great, but the ability to communicate the results of an evaluation instantly to your transaction system is vital to keeping your customers safe. Through code contributed by **Paysys Labs**, Tazama 2.1.0 facilitates the high-speed egress of evaluation results to your transaction and case management systems through a variety of protocols.

- **The Tazama Demo UI**: We are very proud to also include a user-friendly interface with Tazama 2.1.0 which will make showcasing the capabilities and features of Tazama so much easier for our community of system integrators and implementation partners. The initial response to our UI has been phenomenal, and we are deeply grateful to **AO Group** for their sterling work in building this interface.

![Tazama Demo UI](/image/feature-release-v2.1.0-demo-ui.png)

- **Easier exploration and deployment**: Our engineering team has been hard at work finding ways to make the implementation and exploration of Tazama easier. From release 2.1.0 onwards, Tazama components will be published on DockerHub as complete images, making the installation process for exploration and contribution, as well as deployment, much easier.

## About Tazama:

Tazama is an open-source transaction monitoring system dedicated to enhancing security and trust in digital ecosystems. By leveraging community collaboration and cutting-edge technology, Tazama aims to provide robust, real-time fraud detection and prevention.

**Join the Tazama Community:**

As always, we invite developers, financial experts, and tech enthusiasts to join us on this exciting journey! Contribute to the Tazama project, help shape its future, and be part of a community committed to making the digital world safer.

For more information, visit our website at www.tazama.org or join our community on Slack at slack.tazama.org.

Contact:

info@tazama.org

## About the Linux Foundation:

The Linux Foundation is dedicated to building sustainable ecosystems around open-source projects to accelerate technology development and industry adoption. With the support of the world's leading developers and companies, the Linux Foundation promotes the growth of the most critical open-source technologies.
