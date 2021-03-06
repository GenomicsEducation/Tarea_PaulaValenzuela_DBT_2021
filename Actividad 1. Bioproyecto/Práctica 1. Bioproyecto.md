## *Genoma del salmón del Atlántico en Assembly, Refseq y Bioproyectos EN SRA*

1.1) Assembly

  **CSASG_v2**
 
  - Nombre del Organismo: Salmo salar (Atlantic salmon)
  - Nombre inespecifico: Salmón Atlantico
  - Raza: aislado doble haploide 
  - Sexo: Hembra 
  - Biomuestra: SAMN02749551 <https://www.ncbi.nlm.nih.gov/biosample/SAMN02749551/>
  - Projecto: PRJNA72713 <https://www.ncbi.nlm.nih.gov/bioproject/PRJNA72713/>
  - Remitente : International Cooperation to Sequence the Atlantic Salmon Genome
  - Fecha: 2015/06/10
  - Nivel de Ensamblel: Cromosoma
  - Representacion del genoma: Completo
  - Categoria RefSeq : genoma representativo
  - Acceso GenBank assembly : GCA_000233375.4 (latest)
  - Acceso RefSeq assembly : GCF_000233375.1 (latest)
  - identico RefSeq assembly y GenBank assembly: no 
  - WGS Project: AGKD04 <https://www.ncbi.nlm.nih.gov/nuccore/AGKD00000000.4/>
  - Método Ensamble: MaSuRCA v. 2.0.3
  - Tecnología de secuanción: Illumina HiSeq; PacBio; Sanger; Illumina GAIIx

#### Este es un nuevo ensamble de todo el genoma del Salmón del Atlántico. El ensamble fue realizado con MaSuRCA v. 2.0.3 y post procesado para lograr cerrar los espacios de los andamios se utilizaron secuencias de otros ensamblajes. La muestra de ADN fue extraida desde el músculo de un donor doble haploide. 

### Estadisticas Globales
  
  |longitud de la secuencia total| 2,966,890,203| 
  |------------|--------------|
  |Longitud total sin espacios   | 2,618,890,303|
  |Gaps entre andamios| 9,418|  
  |Número total de cromosomas y plásmidios| 30| 
 
1.2) RefSeq 
  **CSASG_v2** 
  
#### Aceso = Público
#### Fuente = DNA(7,164), RNA(3,779)
#### Type =genome(1,283)
#### Dispoción de la biblioteca = pares(6,805), simple(4,340)
#### Plataformas=
-ABI SOLiD(31)   
-BGISEQ(13)   
-Capillary(321)   
-Illumina(10,514)   
-Ion Torrent(132)   
-LS454(11)   
-Oxford Nanopore(14)   
-PacBio SMRT(109)  

#### Estrategías= EpiGenomics(314), Exome(425)
#### Genome(1,605)
#### other(8,801)
#### Tipo de fila= bam(394)
##### -fastq(9,009)
##### -sff(4)
##### -* Datos alineados* =(152)
##### -Link de accceso muestra *ERX4787613*
##### -Número de referencia de la Muestra= ERX4787613: HiSeq X Ten paired end sequencing; Raw reads: Library_IoA-00,Sample_IoA-00_9(A9)
##### -subido por =Institute of Aquaculture, University of Stirling, Stirling, UK (Institute of Aquaculture, University of Stirling, )
##### -Muestra: Laboratory strain IoA-00, SAMEA7690915 • ERS5447441
##### - Organism: Lepeophtheirus salmonis

|Run	| N°of Spots|	N° of Bases|	Size|	Published|
|----|-----|-----|-----|-----|
|ERR4968416|	27,846,466	|8.4G	|2.5Gb	|2021-05-12|

1.3) SRA

#### **SRX11031278** : 16S rRNA microbioma intestinal de salmón del atlántico juvenil <https://www.ncbi.nlm.nih.gov/sra/SRX11031278[accn]>
##### 1 ILLUMINA (Illumina MiSeq) run: 71,300 spots, 38.9M bases, 22.5Mb descarga

#### Diseño: el ADN de cada muestra de intestino se sometió a PCR de una región que cubre la región V3-V4 del gen rRNA 16S utilizando el par de cebadores bacterianos universales SD-Bact-0341-bS-17 (5-CCTACGGGNGGCWGCAG-3) / SD- Bact-0785-aA-21 (5-GACTACHVGGGTATCTAATCC-3) (Klindworth et al., 2013). Las reacciones de PCR se configuraron utilizando 10 ng de ADN molde, 5 l de tampón 5X Phusion HF (New England BioLabs), dNTP 200 M, cebadores directos 0,5 M y inversos 0,5 M que contienen adaptadores de proyección Illumina, 0,2 l de ADN polimerasa de alta fidelidad Phusion y agua libre de nucleasas hasta un volumen total de reacción de 25 l. Las condiciones del termociclador se establecieron con un paso de desnaturalización inicial a 98ºC durante 30 s seguido de 30 ciclos de: desnaturalización a 98ºC durante 10 s, hibridación a 52ºC durante 30 sy extensión a 72ºC durante 30 s. La extensión final se fijó a 72ºC durante 5 min. Las bibliotecas se multiplexaron utilizando códigos de barras Nextera XT v2 (Illumina), se normalizaron en placas de normalización Sequel-Prep (ThermoFisher Scientific) y se secuenciaron en un secuenciador de escritorio MiSeq (Illumina) utilizando química v3 y 2 x 300 ciclos.

|Estudio: Metamorphosis_salmongut_insectmeal|--------|
|------------|----------------------|
|PRJNA733893|<https://www.ncbi.nlm.nih.gov/bioproject/PRJNA733893>
|SRP321989|<https://trace.ncbi.nlm.nih.gov/Traces/sra/?study=SRP321989|

#### Abstract: Diferentes tratamientos de larvas de mosca para alimentar a alevines de salmón del Atlántico (Salmo salar) para evaluar el impacto en el microbioma intestinal.

### Biblioteca:
|Nombre| BSFC-tank3replicate3|
|------|------------|
|Instrumento| Illumina MiSeq|
|Estrategia| AMPLICON|
|Fuente| METAGENOMIC|
|Selección| PCR|

|Run| # of Spots|	# of Bases|	Size	Published|
|---|-----------|-----------|----------------|
|SRR14693097|	71,300	|38.9M|	22.5Mb|	2021-05-31|


