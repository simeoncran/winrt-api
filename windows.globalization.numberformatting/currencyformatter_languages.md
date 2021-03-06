---
-api-id: P:Windows.Globalization.NumberFormatting.CurrencyFormatter.Languages
-api-type: winrt property
---

<!-- Property syntax
public Windows.Foundation.Collections.IVectorView<string> Languages { get; }
-->

# Windows.Globalization.NumberFormatting.CurrencyFormatter.Languages

## -description
Gets the priority list of language identifiers that is used when formatting and parsing currency values.

## -property-value
The priority list of language identifiers.

**Starting in :** Language tags can support Unicode extensions. See the Remarks for the [CurrencyFormatter(String, IIterable(String), String)](currencyformatter_currencyformatter_1781948400.md) constructor.

## -remarks
If your app passes language tags from this class to any [National Language Support](https://docs.microsoft.com/windows/desktop/Intl/national-language-support) functions, it must first convert the tags by calling [ResolveLocaleName](https://docs.microsoft.com/windows/desktop/api/winnls/nf-winnls-resolvelocalename).

## -examples

## -see-also
