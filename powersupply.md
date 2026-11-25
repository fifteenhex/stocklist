# DC-DC/LDO/PMIC/Charger/Load Switch

| vendor                 | part number     | package | quantity | location      | notes          | source  | datasheet               |
|------------------------|-----------------|---------|----------|---------------|----------------|---------|-------------------------|
| Qorvo                  | ACT8865QI305-T  | TQFN 32 | 2        |               |                |         | [Product page][act8865] |
| Everanalog             | EA3036C         |         | LOTS     |               | 3 x DC-DC      |         | [Datasheet][ea3036c]    |
| Everanalog             | EA3056          |         | 100      |               |                |         | [Datasheet][ea3056]     |
| Silergy                | SY8205FCC       |         | lots     | dc-dc etc box | step down      |         | [Datasheet][sy8205]     |
| richtech               | RT8059gj5       | sot 23  | lots     | dc-dc etc box | buck           | taobao  | [Datasheet][rt8059]     |
| Injoinic               | ip6103          |         | 30       | dc-dc etc box | pmic           |         |                         |
|                        | lxdc55faaa-203  |         | 1        |               | dc-dc          |         | [Datasheet][lxdc55]     |
| TI                     | tps63001drcr    | QFN     | 4        | dc-dc etc box | buck-boost     | digikey | [Datasheet][tps63001]   |
| TI                     | lmz20502silt    | LGA     | 5        | dc-dc etc box |                | digikey | [Datasheet][lmz20502]   |
| TI                     | lmz10503tze-adj | xxx     | 1        | dc-dc etc box |                | digikey | [Datasheet][lmz10503]   |
| ablic                  | s-812c33ay-b-g  |         | 5        | dc-dc etc box | 3.3v 50mA LDO  | akizuki | [Datasheet][s812c]      |
| ablic                  | s-812c50ay-b-g  |         | 6        | dc-dc etc box | 5v 70ma LDO    | akizuki | [Datasheet][s812c]      |
| MICRONE                | me6206a33xg     | sot     | 2        | dc-dc etc box | 3.3v 300mA LDO | aitendo | [Datasheet][me6206]     |
| torex                  | xc6206p332      | sot     | LOTS     | dc-dc etc box | 3.3v LDO       | taobao  | [Datasheet][xc6206]     |
| microchip              | mcp1640t        | sot     | 2        | dc-dc etc box | boost          |         | [Datasheet][mcp1640]    |
| microchip              | tc962epa        | dip8    | 4        | dc-dc etc box | hv dc-dc conv  |         | [Datasheet][tc962]      |
| murata                 | okl-t/3-w5n-c   | LGA     | 2        | dc-dc etc box | dc-dc module   | akizuki | [Product page][okl]     |

## Charger

| vendor                 | part number     | package | quantity | location      | notes         | source | datasheet           |
|------------------------|-----------------|---------|----------|---------------|---------------|--------|---------------------|
| richtek                | RT9525          | QFN     | 9        | dc-dc etc box | lipo charger  | taobao | [Datasheet][rt9525] |

## Load switch

| vendor                 | part number     | package | quantity | location      | notes         | source | datasheet            |
|------------------------|-----------------|---------|----------|---------------|---------------|--------|----------------------|
| Silergy                | SY6288AAAAC     | sot23-6 | 50?      | dc-dc etc box | active high   | taobao | [Datasheet][sy6288]  |
| Silergy                | SY6283A         | DFN     | 20?      | dc-dc etc box |               | taobao | [Datasheet][sy6283a] |
| Silergy                | SY6283DRC       | DFN     | 40       | dc-dc etc box |               | taobao | [Datasheet][sy6283]  |
| Microchip              | MIC2505-1YM     |         | 3        | dc-dc etc box |               |        | [Datasheet][mic2505] |

# PSU

| vendor                 | part number     | package | quantity | location                    | notes         | datasheet           |
|------------------------|-----------------|---------|----------|-----------------------------|---------------|---------------------|
| cosel                  | PBA50F-36       | block   | 2        | Brown bookcase, brown boxes | 36V mains PSU | [Datasheet][pba50f] |

[act8865]: https://www.qorvo.com/products/p/ACT8865 "ACT8865 product page; datasheet Rev H under Technical Documents"
[ea3036c]: https://www.lcsc.com/datasheet/C570857.pdf "EA3036C 3ch PMIC datasheet (LCSC)"
[ea3056]: https://www.lcsc.com/datasheet/C575411.pdf "EA3056 3ch DC-DC + LDO PMIC datasheet (LCSC)"
[sy8205]: https://www.lcsc.com/datasheet/C111875.pdf "SY8205 5A 30V synchronous step-down (LCSC)"
[rt8059]: https://www.richtek.com/assets/product_file/RT8059/DS8059-06.pdf "RT8059 1.5MHz 1A step-down, DS8059-06"
[lxdc55]: https://www.murata.com/~/media/webrenewal/products/ecoproducts/lxdc55faaa-203_datasheet_e.ashx?la=ja-jp "LXDC55FAAA-203 micro DC-DC converter"
[tps63001]: https://www.ti.com/lit/ds/symlink/tps63001.pdf "TPS6300x buck-boost converter"
[lmz20502]: https://www.ti.com/lit/ds/symlink/lmz20502.pdf "LMZ20502 2A nano module"
[lmz10503]: https://www.ti.com/lit/ds/symlink/lmz10503.pdf "LMZ10503 3A SIMPLE SWITCHER module"
[s812c]: https://www.ablic.com/en/doc/datasheet/voltage_regulator/S812C_E.pdf "S-812C series 16V input 75mA LDO with ON/OFF"
[me6206]: https://www.lcsc.com/datasheet/C161345.pdf "ME6206A33XG 300mA LDO (LCSC)"
[xc6206]: https://product.torexsemi.com/system/files/series/xc6206.pdf "XC6206 series 200mA LDO"
[mcp1640]: https://ww1.microchip.com/downloads/aemDocuments/documents/APID/ProductDocuments/DataSheets/MCP1640-Family-Data-Sheet-DS20002234E.pdf "MCP1640 family synchronous boost, DS20002234E"
[tc962]: https://ww1.microchip.com/downloads/aemDocuments/documents/APID/ProductDocuments/DataSheets/21484D.pdf "TC962 high current charge pump, DS21484D"
[rt9525]: https://www.richtek.com/assets/product_file/RT9525/DS9525-03.pdf "RT9525 single cell Li-ion charger, DS9525-03"
[sy6288]: https://www.lcsc.com/datasheet/C111829.pdf "SY6288 low loss power distribution switch (LCSC)"
[sy6283a]: https://www.lcsc.com/datasheet/C412142.pdf "SY6283/SY6283A 3A load switch (LCSC)"
[sy6283]: https://www.lcsc.com/datasheet/C178243.pdf "SY6283/SY6283A 3A load switch (LCSC)"
[mic2505]: https://ww1.microchip.com/downloads/en/DeviceDoc/20005579A.pdf "MIC2505/6 high-side switches, DS20005579A"
[pba50f]: https://www.cosel.com/tool/tag.php/pdf/SFE_PBA-PBW.pdf "Cosel PBA/PBW series spec sheet"
[okl]: https://www.murata.com/en-us/products/productdetail?partno=OKL-T/3-W5N-C "OKL-T/3-W5 product page with datasheet download; murata PDF host returned errors when checked"
