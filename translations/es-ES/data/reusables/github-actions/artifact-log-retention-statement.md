{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.22" %} Predeterminadamente, {% data variables.product.product_name %} almacena las bitácoras de compilación y los artefactos por 90 días, y este periodo de retención se puede personalizar. Para obtener más información, consulta la sección "[Límites de uso, facturación y administración](/actions/reference/usage-limits-billing-and-administration#artifact-and-log-retention-policy)".{% endif %}
{% if currentVersion == "enterprise-server@2.22" %} Las {% data variables.product.product_name %} almacenan las bitácoras y los artefactos por 90 días.{% endif %}