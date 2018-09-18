# fishbase-sealifebase-archiver

Tabular archives generated from FishBase and SeaLifeBase database. Precompiled archives can be found in the [releases](../../releases) section.

Please attribute Fishbase and SeaLifeBase when using the output of this archiver. You can find citation/ attribution guidelines on the respective webpages. At time of writing (Feb 2017), both Fishbase and SeaLifeBase was licensed under [Creative Commons Attribution-Noncommercial 3.0 Unported License](https://creativecommons.org/licenses/by-nc/3.0/).

## expected results

The archives are gzip compressed, tab separated files. The first few lines of ```stocks_fishbase.tsv.gz``` look like:

```tsv
StockCode	SpecCode	StockDefs	StockDefsGeneral	Level	LocalUnique	IUCN_Code	IUCN_Assessment	Protected	StocksRefNo	CITES_Code	CITES_Date	CITES_Ref	CITES_Remarks	Northernmost	NorthSouthN	Southermost	NorthSouthS	Westernmost	WestEastW	Easternmost	WestEastE	BoundingRef	BoundingMethod	TempMin	TempMax	TempRef	EnvTemp	Resilience	ResilienceRemark	pHMin	pHMax	pHRef	dHMin	dHMax	dHRef	GenBankID	RfeID	FIGIS_ID	EcotoxID	SCRFA_data	GMAD_ID	SAUP	SAUP_ID	SAUP_Group	AusMuseum	FishTrace	IUCN_ID	IUCN_Group	BOLD_ID	IGFAName	EssayID	ICESStockID	OsteoBaseID	DORIS_ID	Aquamaps	Morphology	Occurrence	Strains	Ecology	Diseases	Abnorm	Metabolism	Predators	Spawning	Fecundity	Speed	Diet	Eggs	EggDevelop	Food	Larvae	LarvDyn	LarvSpeed	PopDyn	LengthWeight	Gillarea	Maturity	MatSizes	Processing	Reproduction	Introductions	Abundance	Vision	Genetics	Aquaculture	CountryComp	Allele	GeneticStudies	Ration	Foods	Ecotoxicology	Brains	Catches	FAOAqua	LengthRelations	LengthFrequency	Sounds	Broodstock	EggNursery	FryNursery	LarvalNursery	Entered	DateEntered	Modified	DateModified	Expert	DateChecked	TS
1884	6	Atlantic, Indian and Pacific:  in tropical and subtropical waters. Highly migratory species, Annex I of the 1982 Convention on the Law of the Sea (Ref. 26139).	Atlantic, Indian and Pacific	species in general	Atlantic, Indian and Pacific:  in tropical and sub	LC	null	0	6376	null	null	null	null	47	N	38	S	180	W	180	E	54341	1	21	30	26	subtropical	High	K=0.4-1.2; tm<1; tmax=5; Fec=85,000	null	null	null	null	null	null	34814	mh	3130	null	0	null	1	600006	1	384	0	154712	null	13788	Dolphinfish	null	null	194	null	1	1	1	0	1	1	1	1	1	1	1	1	1	1	1	1	1	0	0	1	1	1	1	1	1	1	0	1	1	0	0	1	1	0	1	1	0	1	1	0	1	1	0	1	1	1	1	2	1990-10-18T00:00:00.000Z	949	2014-10-14T00:00:00.000Z	133	1996-02-27T00:00:00.000Z	null
```
