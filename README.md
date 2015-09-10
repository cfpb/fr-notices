fr-notices
==========

In a few cases, we edit the XML for a Federal Register notice to make it easy
to parse with our [regulations-parser](https://github.com/cfpb/regulations-parser). We store those changes here.

**Note**: These are unofficial changes. All official notices are available through [the Federal Register](https://www.federalregister.gov/agencies/consumer-financial-protection-bureau).

## Usage

Use these notices with our [regulations-parser](https://github.com/cfpb/regulations-parser) as part of the [eRegulations](http://cfpb.github.io/eRegulations/) project.

## Parsing instructions

Assuming that the `fr-notices` directory is inside of the `regulations-parser` directory:

```bash
# Reg B
./build_from.py fr-notices/annual/CFR-2012-title12-vol8-part1002.xml 12 15 1691

# Reg D
./build_from.py fr-notices/annual/CFR-2012-title12-vol8-part1004.xml 12 15 1604

# Reg E
# Regulation E needs to start from a notice.
./build_from.py fr-notices/articles/xml/201/131/725.xml 12 15 1693

# Reg J
./build_from.py fr-notices/annual/CFR-2012-title12-vol8-part1010.xml 12 15 1702

# Reg K
./build_from.py fr-notices/annual/CFR-2012-title12-vol8-part1010.xml 12 15 1702

# Reg L
./build_from.py fr-notices/annual/CFR-2012-title12-vol8-part1012.xml 12 15 1718

# Reg M
./build_from.py fr-notices/annual/CFR-2012-title12-vol8-part1013.xml 12 15 1601

# Reg X
./build_from.py fr-notices/annual/CFR-2012-title12-vol8-part1024.xml 12 15 16021

# Reg Z
./build_from.py fr-notices/annual/CFR-2012-title12-vol8-part1026.xml 12 15 1601
```

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)
