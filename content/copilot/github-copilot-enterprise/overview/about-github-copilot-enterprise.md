---
title: About GitHub Copilot Enterprise
shortTitle: About Copilot Enterprise
intro: 'Learn about {% data variables.product.prodname_copilot_enterprise %} and how it compares to other {% data variables.product.prodname_copilot_short %} plans.'
product: '{% data reusables.gated-features.copilot-billing %}'
versions:
  feature: copilot
topics:
  - Copilot
---


{% ifversion fpt %}

{% data reusables.copilot.enterprise-fpt-link %}

{% endif %}

{% data reusables.copilot.get-copilot-enterprise-cta-button %}

## About {% data variables.product.prodname_copilot_enterprise_short %}

{% data reusables.copilot.about-copilot %}

{% data variables.product.prodname_copilot_enterprise %} is a {% data variables.product.prodname_copilot_short %} plan available for enterprises that use {% data variables.product.prodname_ghe_cloud %}. It provides AI features to enhance your experience on {% data variables.product.prodname_dotcom_the_website %}, such as the ability to chat with {% data variables.product.prodname_copilot_short %} in the browser and reference context for {% data variables.product.prodname_copilot_short %} from across your project repositories. For more information, see "[AUTOTITLE](/copilot/github-copilot-enterprise/overview/github-copilot-enterprise-feature-set)." For details of the differences between {% data variables.product.prodname_copilot_enterprise %} and the other {% data variables.product.prodname_copilot_short %} plans, see the comparison table below.

Enterprise owners can allow some or all organizations in the enterprise to access {% data variables.product.prodname_copilot %}. If an organization has access to {% data variables.product.prodname_copilot_short %}, owners of the organization can assign {% data variables.product.prodname_copilot_enterprise_short %} seats to some or all members of the organization. {% ifversion ghec %}For more information, see "[AUTOTITLE](/copilot/github-copilot-enterprise/overview/enabling-github-copilot-enterprise-features)."{% endif %}

### Understanding the differences between {% data variables.product.prodname_copilot_business_short %}, {% data variables.product.prodname_copilot_individuals_short %}, and {% data variables.product.prodname_copilot_enterprise_short %}

{% data reusables.copilot.differences-cfi-cfb-table %}

## Setting up and enabling {% data variables.product.prodname_copilot_enterprise_short %}

To use {% data variables.product.prodname_copilot_enterprise_short %}, you need to set up a subscription for your enterprise account. For more information, see "[AUTOTITLE](/enterprise-cloud@latest/billing/managing-billing-for-github-copilot/managing-your-github-copilot-enterprise-subscription)."

After setting up a subscription, enterprise owners and organization owners can enable {% data variables.product.prodname_copilot_enterprise_short %} for their enterprise or organization. For more information, see "[AUTOTITLE](/copilot/github-copilot-enterprise/overview/enabling-github-copilot-enterprise-features)."

## Assigning {% data variables.product.prodname_copilot %} seats

To use the features of {% data variables.product.prodname_copilot_enterprise_short %} you must have access to {% data variables.product.prodname_copilot %}.

Access to {% data variables.product.prodname_copilot %} is managed at the organization level. To give people or teams within an organization access to {% data variables.product.prodname_copilot %}, an organization owner must assign each individual a {% data variables.product.prodname_copilot %} seat. Organization owners can grant access to all current and future users in the organization, or just to specific users. For more information, see "[AUTOTITLE](/copilot/managing-github-copilot-in-your-organization/managing-access-for-copilot-business-in-your-organization)."

## About billing for {% data variables.product.prodname_copilot_enterprise_short %}

{% data variables.product.prodname_copilot_enterprise_short %} subscriptions are billed monthly, based on the number of {% data variables.product.prodname_copilot %} seats assigned to users within your enterprise. For more information, see "[AUTOTITLE](/billing/managing-billing-for-github-copilot/about-billing-for-github-copilot#pricing-for-github-copilot-enterprise)."

## Further reading

- "[{% data variables.product.prodname_copilot %} FAQ](https://github.com/features/copilot#faq)"
