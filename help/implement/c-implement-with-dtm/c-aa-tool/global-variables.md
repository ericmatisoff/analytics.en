---
description: Field descriptions and information about variables when using Dynamic Tag Management to deploy Adobe Analytics.
keywords: Dynamic Tag Management;global variables;server variable;evar;props;dynamic variable prefix;dynamic variable
seo-description: Field descriptions and information about variables when using Dynamic Tag Management to deploy Adobe Analytics.
seo-title: Global variables
solution: Marketing Cloud,Analytics,Dynamic Tag Management
title: Global variables
uuid: d759320a-96ee-4073-b5fd-5257b7033003
---

# Global variables

Field descriptions and information about variables when using Dynamic Tag Management to deploy Adobe Analytics.

These variables fire on all page load rule beacons. You can accomplish the same effect by using a [Page-Load rule](../../../implement/c-implement-with-dtm/c-rules/t-rules-page-conditions.md#task_69B41CB230EE4530A755D91233F73706) set to fire on all pages. These variables might not fire in [Direct-Call](../../../implement/c-implement-with-dtm/c-rules/t-rules-direct-conditions.md#task_85EB8F01775A402BA53B8298F0AADA09) and [Event-Based](../../../implement/c-implement-with-dtm/c-rules/t-rules-event-conditions.md#task_A122DE72110F4579A91F9D96D92D39FC) rules.

## Global Variables - Field Descriptions {#section_2917F62FCC8D43F982B2612A702DEF81}

**[!UICONTROL  *`Property`*]** > ![](assets/settings_gear.png) **[!UICONTROL Edit Tool]** > **[!UICONTROL Global Variables]** 

| Element | Description |
|--- |--- |
|Server|The predefined variable populates the  Servers dimension in Adobe Analytics. See [Page Variables](/help/implement/js-implementation/c-variables/page-variables.md)|
|eVars|[eVar variables](/help/implement/js-implementation/c-variables/page-variables.md) are used for building custom conversion reports.|
|Props|[Prop variables](/help/implement/js-implementation/c-variables/page-variables.md) are used for building custom traffic reports.|
|Dynamic Variable Prefix|A special prefix to the start of the value. The default prefix is "D=". See [Dynamic Variables](/help/implement/js-implementation/c-variables/dynvars-overview.md)|
