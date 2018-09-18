# fishbase-sealifebase-archiver

Tabular archives generated from FishBase and SeaLifeBase database. Precompiled archives can be found in the [releases](../../releases) section.

[![DOI](https://zenodo.org/badge/149221981.svg)](https://zenodo.org/badge/latestdoi/149221981)

## expected results

The archives are gzip compressed, tab separated files. The first few lines of ```stocks_fishbase.tsv.gz``` look like:

```tsv
StockCode	SpecCode	StockDefs	StockDefsGeneral	Level	LocalUnique	IUCN_Code	IUCN_Assessment	Protected	StocksRefNo	CITES_Code	CITES_Date	CITES_Ref	CITES_Remarks	Northernmost	NorthSouthN	Southermost	NorthSouthS	Westernmost	WestEastW	Easternmost	WestEastE	BoundingRef	BoundingMethod	TempMin	TempMax	TempRef	EnvTemp	Resilience	ResilienceRemark	pHMin	pHMax	pHRef	dHMin	dHMax	dHRef	GenBankID	RfeID	FIGIS_ID	EcotoxID	SCRFA_data	GMAD_ID	SAUP	SAUP_ID	SAUP_Group	AusMuseum	FishTrace	IUCN_ID	IUCN_Group	BOLD_ID	IGFAName	EssayID	ICESStockID	OsteoBaseID	DORIS_ID	Aquamaps	Morphology	Occurrence	Strains	Ecology	Diseases	Abnorm	Metabolism	Predators	Spawning	Fecundity	Speed	Diet	Eggs	EggDevelop	Food	Larvae	LarvDyn	LarvSpeed	PopDyn	LengthWeight	Gillarea	Maturity	MatSizes	Processing	Reproduction	Introductions	Abundance	Vision	Genetics	Aquaculture	CountryComp	Allele	GeneticStudies	Ration	Foods	Ecotoxicology	Brains	Catches	FAOAqua	LengthRelations	LengthFrequency	Sounds	Broodstock	EggNursery	FryNursery	LarvalNursery	Entered	DateEntered	Modified	DateModified	Expert	DateChecked	TS
1884	6	Atlantic, Indian and Pacific:  in tropical and subtropical waters. Highly migratory species, Annex I of the 1982 Convention on the Law of the Sea (Ref. 26139).	Atlantic, Indian and Pacific	species in general	Atlantic, Indian and Pacific:  in tropical and sub	LC	null	0	6376	null	null	null	null	47	N	38	S	180	W	180	E	54341	1	21	30	26	subtropical	High	K=0.4-1.2; tm<1; tmax=5; Fec=85,000	null	null	null	null	null	null	34814	mh	3130	null	0	null	1	600006	1	384	0	154712	null	13788	Dolphinfish	null	null	194	null	1	1	1	0	1	1	1	1	1	1	1	1	1	1	1	1	1	0	0	1	1	1	1	1	1	1	0	1	1	0	0	1	1	0	1	1	0	1	1	0	1	1	0	1	1	1	1	2	1990-10-18T00:00:00.000Z	949	2014-10-14T00:00:00.000Z	133	1996-02-27T00:00:00.000Z	null
```

## How to cite FishBase
To give due credit to the original authors, please cite data taken from FishBase by Main Ref. and/or Data Ref. of the respective record.

Cite FishBase itself as<br>
Froese, R. and D. Pauly. Editors. 2018. FishBase.<br>
World Wide Web electronic publication.<br>
www.fishbase.org, version (06/2018).

## Disclaimer
FishBase present information on fishes as correctly as possible. However, we can not exclude errors, and neither we nor our partners can be held responsible for any damage that may arise from these.

## Copyright
Creative Commons License This work is licensed under a [Creative Commons Attribution-Noncommercial 3.0 Unported License (CC-BY-NC)](https://creativecommons.org/licenses/by-nc/3.0/).

You are welcome to include text, numbers and maps from FishBase in your own web sites for non-commercial use, given that such inserts are clearly identified as coming from FishBase, with a backward link to the respective source page. Photos and drawings belong to the indicated persons or organizations and have their own copyright statements. Photos and drawings with CC-BY or CC-BY-NC copyrights can be used without further permission, with full attribution to the person or organization and the indication 'from FishBase'.
