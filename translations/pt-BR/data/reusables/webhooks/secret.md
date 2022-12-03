Definir um segredo de webhook permite que você certifique-se de que as solicitações `POST` enviadas para a URL da carga são de {% data variables.product.product_name %}. When you set a secret, you'll receive the {% ifversion fpt or ghes or ghec %}`X-Hub-Signature` and `X-Hub-Signature-256` headers{% elsif ghae %}`X-Hub-Signature-256` header{% endif %} in the webhook `POST` request. Para obter mais informações sobre como usar um segredo com um cabeçalho de assinatura para proteger as suas cargas do webhook, veja "[Proteger seus webhooks](/webhooks/securing/)."