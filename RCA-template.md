# 0-day Root Cause Analysis Template

# \<CVE\>: \<Description/Title\>

## The Basics

**Disclosure Data:**

**Patch Date:**

**Product:**

**Scope:**

**Advisory:**

**Affected Versions:**

**First Patched Version:**

**Issue/Bug Report:**

**Patch CL:**

**Bug-Introducing CL:**

**Reporter(s):**

## The Code

**Proof-of-concept:**

**Exploit sample:**

**Did you have access to the exploit sample when doing the analysis?**

## The Vulnerability

**Bug class:**

**Vulnerability details:**

**(Historical/present/future) context of bug:**

### Detection reproducer

**Fuzzing reproducer**:

**Code auditing reproducer**:

**Static analysis reproducer**:

**Variant analysis reproducer**:

## The Exploit

The terms *exploit primitive*, *exploit strategy*, *exploit technique*, and
*exploit flow* are [defined here](https://googleprojectzero.blogspot.com/2020/06/a-survey-of-recent-ios-kernel-exploits.html).

**Exploit strategy (or strategies):**

**Exploit flow:**

**Known cases of the same exploit flow:**

**Part of an exploit chain?**

## The Patch

**Mitigation strategy (or strategies):**

**Was there a temporary workaround before the release of a working patch?**

**Patch diffing reproducer:**

**Patch analysis:**

**Results of Patch fuzzing:**

**Patch gapping time-frame:**

## The Next Steps

### Variant analysis

**Areas/approach for variant analysis (and why):**

**Found variants:**

### Structural improvements

make this type of vulnerability harder to exploit, etc.?

**Ideas to kill the bug class:**

**Ideas to prevent the introduction of this vulnerability:**

**Ideas to mitigate the exploit flow:**

**Ideas to make it harder to exploit:**

**Other potential improvements:**

### 0-day detection methods

What are potential detection methods for similar 0-days? Meaning are there any
ideas of how this exploit or similar exploits could be detected **as a 0-day**?

## Other References

### Links

