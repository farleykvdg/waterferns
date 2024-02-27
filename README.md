# waterferns
Assembly of Salviniales fern organelle genomes and analysis of RNA editing in their transcripts. Also, comparative evolutionary analysis of RNA editing proteins and phylogenetics of RNA editing sites and putative RNA editing proteins.

Water Ferns

Investigators: Farley Kwok van der Giezen, Ian Small

Required software:
BBtools, SPAdes, NOVOPlasty, samtools, GetOrganelle, HMMer, MAFFT, Julia language environment
PPRfinder.jl, PPRmatcher.jl, orfinder.jl, pyrimid.jl, edit_genome.jl, chloe.jl, read_depth_coverage_single.jl, editing_calls.jl, extract_proteins.jl, translation_check.jl, mapsites.jl, nt2codon.jl

This project aims to assemble the plastome and mitochondrion genomes of species of aquatic ferns from Western Australia, and to characterise the RNA editing events within the two organelle transcriptomes.
Additionally, pentatricopeptide repeat protein editing factors will be catalogued and divided into orthogroups, and an attempt to match them to organelle RNA editing events will be made.
DNAseq and RNAseq libraries from four aquatic fern species (Azolla pinnata, Azolla rubra, Marsilea mutica, Salvinia molesta) are the primary data used to assemble organelle genomes, and to determine RNA editing events in the organelle transcriptomes.

The directory structure of this project is as follows:

>00_scripts
#julia scripts and custom code is stored here
	
>01_dnaseq 
#raw dna sequence data is stored here
	>apinnata
	>arubra
	>mmutica
	>smolesta

>02_rnaseq
#raw rna sequence data is stored here
	>apinnata
	>arubra
	>mmutica
	>smolesta

>03_assemblies
#chloroplast and mitochondria assemblies are stored here
	>chloroplast
		>apinnata
		>arubra
		>mmutica
		>smolesta
	>mitochondria
		>apinnata
		>arubra
		>mmutica
		>smolesta

>04_rnaediting
#analysis of rna editing events is stored here
	>apinnata
	>arubra
	>mmutica
	>smolesta

>05_transcriptomes
#transcriptome assemblies are stored here
	>apinnata
	>arubra
	>mmutica
	>smolesta

>06_pprproteins
#analysis of ppr proteins is stored here
	>apinnata
	>arubra
	>mmutica
	>smolesta

>07_results
#results for download to local storage are moved here
