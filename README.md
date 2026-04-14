# cybrosys
Este repositorio contiene módulos de Cybrosys Addons utilizados en los proyectos.

## Módulo `subscription_package`

El módulo `subscription_package` es un desarrollo de **Cybrosys Technologies** que proporciona funcionalidades avanzadas para la gestión de suscripciones en Odoo. Este módulo incluye características como la creación y gestión de planes de suscripción, la automatización de facturación recurrente, la configuración de etapas de suscripción, y más.

### Dependencias
Para su correcto funcionamiento, este módulo requiere que las siguientes dependencias estén instaladas previamente en el sistema:

- `base`
- `mail`
- `sale_management`
- `account`

### Módulos que dependen de `subscription_package`

Los siguientes módulos propios de Calyx tienen `subscription_package` en su `depends`, por lo que requieren que esté instalado para funcionar:

- `subscripcion_force_invoice`
- `subscription_massive_update`
- `fix_credit_note_subscription`
- `sale_order_subscription`
- `subscription_button`
- `show_analytic_accounts`
- `fix_invoice_count_subscription`

### Módulos que referencian a `subscription_package`

Adicionalmente, los siguientes módulos no lo declaran como dependencia, pero sí lo referencian en vistas o datos (xmlids, herencias de vistas, etc.), por lo que también podrían verse afectados si el módulo no está presente:

- `custom_access_permissions`
- `sale_subscrsale_subscription_custom_fields`

Es importante asegurarse de que el módulo `subscription_package` esté instalado y configurado correctamente para evitar problemas en los módulos que dependen de él o lo referencian.
