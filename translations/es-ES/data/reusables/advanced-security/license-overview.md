Cada licencia de {% data variables.product.prodname_GH_advanced_security %} especifica una cantidad máxima de cuentas o de plazas que pueden utilizar estas características. Cada confirmante activo en por lo menos un repositorio con la característica habilitada utilizará una plaza. A committer is considered active if one of their commits has been pushed to the repository within the last 90 days, regardless of when it was originally authored.

{% note %}

**Note:** Active committers are calculated using both the commit author information and the timestamp for when the code was pushed to {% data variables.product.product_name %}.

- When a user pushes code to {% data variables.product.prodname_dotcom %}, every user who authored code in that push counts towards {% data variables.product.prodname_GH_advanced_security %} seats, even if the code is not new to {% data variables.product.prodname_dotcom %}.

- Users should always create branches from a recent base, or rebase them before pushing. This will ensure that users who have not committed in the last 90 days do not take up {% data variables.product.prodname_GH_advanced_security %} seats.

{% endnote %}

