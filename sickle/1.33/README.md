# Sickle Container
Main tool: [Sickle](https://github.com/najoshi/sickle)


Sickle is a windowed adaptive trimming tool for FASTQ files using quality


# Example Usage

## single end
```
sickle se -f input_file.fastq -t illumina -o trimmed_output_file.fastq
```

## paired end
```
sickle pe -f input_file1.fastq -r input_file2.fastq -t sanger \
-o trimmed_output_file1.fastq -p trimmed_output_file2.fastq \
-s trimmed_singles_file.fastq
```

