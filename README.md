<p align="center">
  <img src="./MINT-LICENSE.png" width="64" height="64" alt="MINT License Suite logo" />
</p>

<h1 align="center">MINT LICENSE Suite</h1>

<p align="center">
  Open source licenses for distinct use cases, intended to be used together.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Overview
</p>

<p align="center">
This repository is the authoritative source for the MINT License Suite. The license texts published here are the canonical versions.
</p>

<p align="center">
MINT is not a single license. It is a base license plus a set of modules. The base license grants rights and sets shared terms. Each module adds one specific obligation on top. Modules are combined additively: <code>MINT + CODE</code>, <code>MINT + SOFTWARE + CODE</code>, <code>MINT + CODE + PUBLIC</code>, and so on. Any combination that matches your use case is valid.
</p>

<p align="center">
The license texts in this repository are released under CC0 1.0. See <a href="#copyright-and-licensing">Copyright and Licensing</a>.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  The Licenses
</p>

<p align="center">
The Suite consists of one base license and five modules. The base license is always required. Modules are additive.
</p>

<table align="center">
  <thead>
    <tr>
      <th align="center">Component</th>
      <th align="center">Role</th>
      <th align="center">Adds</th>
      <th align="center">File</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><strong>MINT</strong></td>
      <td align="center">Base license</td>
      <td align="center">Copyright grant, patent grant, attribution, disclaimer, termination</td>
      <td align="center"><code>LICENSE-MINT</code></td>
    </tr>
    <tr>
      <td align="center"><strong>MINT-CODE</strong></td>
      <td align="center">Module</td>
      <td align="center">File-level reciprocity for source code</td>
      <td align="center"><code>LICENSE-MINT-CODE</code></td>
    </tr>
    <tr>
      <td align="center"><strong>MINT-SOFTWARE</strong></td>
      <td align="center">Module</td>
      <td align="center">Notice on product distribution</td>
      <td align="center"><code>LICENSE-MINT-SOFTWARE</code></td>
    </tr>
    <tr>
      <td align="center"><strong>MINT-PUBLIC</strong></td>
      <td align="center">Module</td>
      <td align="center">Supersession of CODE for official API access</td>
      <td align="center"><code>LICENSE-MINT-PUBLIC</code></td>
    </tr>
    <tr>
      <td align="center"><strong>MINT-DESIGN</strong></td>
      <td align="center">Module</td>
      <td align="center">Notice on design integration; trademark exclusion</td>
      <td align="center"><code>LICENSE-MINT-DESIGN</code></td>
    </tr>
    <tr>
      <td align="center"><strong>MINT-DATA</strong></td>
      <td align="center">Module</td>
      <td align="center">Source notice; share-alike for derivative datasets</td>
      <td align="center"><code>LICENSE-MINT-DATA</code></td>
    </tr>
  </tbody>
</table>

<div style="height: 40px;"></div>

<p align="center">
The base license can be used alone. Used alone, it grants rights without imposing reciprocity, notice, or share-alike obligations. This is useful for permissive projects that want the MINT attribution and patent terms without copyleft.
</p>

<p align="center">
SPDX identifiers:
</p>

```
LicenseRef-MINT-1.0
LicenseRef-MINT-CODE-1.0
LicenseRef-MINT-SOFTWARE-1.0
LicenseRef-MINT-PUBLIC-1.0
LicenseRef-MINT-DESIGN-1.0
LicenseRef-MINT-DATA-1.0
```

<div style="height: 40px;"></div>

<p align="center">
Short identifiers for documentation and component mapping:
</p>

<table align="center">
  <thead>
    <tr>
      <th align="center">Component</th>
      <th align="center">Short</th>
    </tr>
  </thead>
  <tbody>
    <tr><td align="center">MINT</td><td align="center"><code>MI</code></td></tr>
    <tr><td align="center">MINT-CODE</td><td align="center"><code>CD</code></td></tr>
    <tr><td align="center">MINT-SOFTWARE</td><td align="center"><code>SW</code></td></tr>
    <tr><td align="center">MINT-PUBLIC</td><td align="center"><code>PB</code></td></tr>
    <tr><td align="center">MINT-DESIGN</td><td align="center"><code>DS</code></td></tr>
    <tr><td align="center">MINT-DATA</td><td align="center"><code>DT</code></td></tr>
  </tbody>
</table>

<p align="center">
Short identifiers are for human readability only. They do not replace SPDX identifiers in formal notices.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Core Design
</p>

<p align="center">
The base license grants rights. Each module adds one obligation. Modules are combined additively. There is no "product license" and no "component license" as separate categories; there is one base and five modules that can be applied to any work.
</p>

<p align="center">
A module is defined by the <strong>behavior</strong> it constrains, not by the type of work. <code>CODE</code> constrains the act of modifying a source file. <code>SOFTWARE</code> constrains the act of distributing a product. <code>PUBLIC</code> constrains the act of accessing through an official API. <code>DESIGN</code> constrains the act of integrating visual elements. <code>DATA</code> constrains the act of deriving from a dataset.
</p>

<div style="height: 40px;"></div>

<p align="center" style="font-size: 20px; font-weight: bold;">
  The Five Behaviors
</p>

<table align="center">
  <thead>
    <tr>
      <th align="center">Behavior</th>
      <th align="center">Module</th>
      <th align="center">Obligation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Modify a source file</td>
      <td align="center"><strong>CODE</strong></td>
      <td align="center">License the modified file under the same module</td>
    </tr>
    <tr>
      <td align="center">Distribute a product</td>
      <td align="center"><strong>SOFTWARE</strong></td>
      <td align="center">Provide a notice identifying the MINT modules applied</td>
    </tr>
    <tr>
      <td align="center">Access through an official API</td>
      <td align="center"><strong>PUBLIC</strong></td>
      <td align="center">The CODE obligation does not apply to that access</td>
    </tr>
    <tr>
      <td align="center">Integrate visual elements</td>
      <td align="center"><strong>DESIGN</strong></td>
      <td align="center">Provide a notice; trademarks are excluded</td>
    </tr>
    <tr>
      <td align="center">Derive from a dataset</td>
      <td align="center"><strong>DATA</strong></td>
      <td align="center">License the derivative dataset under the same module</td>
    </tr>
  </tbody>
</table>

<div style="height: 40px;"></div>

<p align="center" style="font-size: 20px; font-weight: bold;">
  How Modules Combine
</p>

<p align="center">
<strong>Parallel.</strong> CODE, SOFTWARE, DESIGN, and DATA are parallel. When more than one applies to the same distribution, their obligations are cumulative. SOFTWARE does not absorb CODE. DESIGN does not absorb SOFTWARE. No module reduces another.
</p>

<p align="center">
<strong>Supersession.</strong> PUBLIC is the only module that supersedes another. When a work is accessed solely through an official API, the CODE obligation does not apply to that access. This is a behavior-level supersession, not a file-level one. Once the user touches source code, the supersession lapses and CODE resumes full effect.
</p>

<p align="center">
<strong>No merging of independent works.</strong> When work A is incorporated into work C, the obligations of A and C are independent. A distributor of C must satisfy the modules of C and the modules of A separately. Satisfying C's CODE does not satisfy A's CODE.
</p>

<div style="height: 40px;"></div>

<p align="center" style="font-size: 20px; font-weight: bold;">
  Worked Example
</p>

<p align="center">
Consider engine A, subsystem B, product C, and an official API D that exposes A and B. A and B are licensed under <code>MINT + CODE</code>. C is licensed under <code>MINT + CODE + SOFTWARE</code>. D is designated as the official API for A and B.
</p>

<table align="center">
  <thead>
    <tr>
      <th align="center">You use</th>
      <th align="center">You must satisfy</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">C's independent code only</td>
      <td align="center">C: MI + CD</td>
    </tr>
    <tr>
      <td align="center">C's code and C's glue layer over A/B</td>
      <td align="center">C: MI + CD &nbsp;+&nbsp; A/B: MI + CD</td>
    </tr>
    <tr>
      <td align="center">C's original copy of A/B</td>
      <td align="center">A/B: MI + CD (treated as taken from A/B, not C)</td>
    </tr>
    <tr>
      <td align="center">C's modified version of A/B</td>
      <td align="center">C: MI + CD &nbsp;+&nbsp; A/B: MI + CD</td>
    </tr>
    <tr>
      <td align="center">A/B through D only</td>
      <td align="center">C: MI + PB &nbsp;(A/B's CD superseded)</td>
    </tr>
    <tr>
      <td align="center">Distribute C as a product</td>
      <td align="center">C: MI + SW &nbsp;(plus CD and any other module that applies)</td>
    </tr>
  </tbody>
</table>

<p align="center">
The <code>&nbsp;+&nbsp;</code> sign means both apply independently. There is no merging and no substitution, except where PUBLIC explicitly supersedes CODE.
</p>

<div style="height: 40px;"></div>

<p align="center" style="font-size: 20px; font-weight: bold;">
  Boundary Conditions
</p>

<p align="center">
<strong>Official API.</strong> The set of interfaces designated by the copyright holder under the CODE module. The designation may point to a file in the same repository, another repository, or a stable URL. If the designation is unreachable, schema-invalid, or lists interfaces the work does not provide, no official API exists for the purposes of PUBLIC.
</p>

<p align="center">
<strong>Invalid designation.</strong> An invalid designation cuts the supersession entirely. CODE continues to apply. The risk of an invalid designation lies with the copyright holder.
</p>

<p align="center">
<strong>Modified API wrapper.</strong> If a user modifies the official API wrapper and embeds or copies source code into it, the supersession lapses for that wrapper, and CODE applies.
</p>

<p align="center">
<strong>Self-written wrappers.</strong> A wrapper not designated as official does not trigger supersession. Access through it is governed by CODE.
</p>

<p align="center">
<strong>Files extracted from C.</strong> If a file obtained from C is substantially equivalent to A or B source, the obligations of A or B apply. The distribution channel does not change the applicable license.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Choosing a Combination
</p>

<p align="center">
Use the table below to determine which modules apply to your action. When an action falls into more than one row, <strong>all</strong> listed modules apply. The base license <code>MINT</code> is always included and is omitted from the table for brevity.
</p>

<table align="center">
  <thead>
    <tr>
      <th align="center">Your action</th>
      <th align="center">Modules</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Copy, modify, or distribute source code</td>
      <td align="center"><strong>CODE</strong></td>
    </tr>
    <tr>
      <td align="center">Distribute a product containing the work</td>
      <td align="center"><strong>SOFTWARE</strong></td>
    </tr>
    <tr>
      <td align="center">Access the work only through an official API</td>
      <td align="center"><strong>PUBLIC</strong> (supersedes CODE for that access)</td>
    </tr>
    <tr>
      <td align="center">Modify an API wrapper without embedding source</td>
      <td align="center"><strong>CODE</strong> (supersession does not apply to the modified wrapper)</td>
    </tr>
    <tr>
      <td align="center">Modify an API wrapper and embed source</td>
      <td align="center"><strong>CODE</strong> (supersession lapses)</td>
    </tr>
    <tr>
      <td align="center">Write your own wrapper around the work</td>
      <td align="center"><strong>CODE</strong> (not an official API)</td>
    </tr>
    <tr>
      <td align="center">Integrate visual elements into a product</td>
      <td align="center"><strong>DESIGN</strong></td>
    </tr>
    <tr>
      <td align="center">Derive from a dataset</td>
      <td align="center"><strong>DATA</strong></td>
    </tr>
  </tbody>
</table>

<div style="height: 40px;"></div>

<p align="center">
When several modules apply, list all of them. Example SPDX expression for a product containing code and design:
</p>

```
SPDX-License-Identifier: LicenseRef-MINT-1.0 AND LicenseRef-MINT-CODE-1.0 AND LicenseRef-MINT-SOFTWARE-1.0 AND LicenseRef-MINT-DESIGN-1.0
```

<p align="center">
If the table and the license texts appear to conflict, the license texts control. The table is a navigation aid.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Repository Layout
</p>

```
/
├── README.md
├── MINT-LICENSE.png
├── CHANGELOG.md
├── licenses/
│   ├── LICENSE
│   ├── en-US/
│   │   ├── LICENSE-MINT
│   │   ├── LICENSE-MINT-CODE
│   │   ├── LICENSE-MINT-SOFTWARE
│   │   ├── LICENSE-MINT-PUBLIC
│   │   ├── LICENSE-MINT-DESIGN
│   │   └── LICENSE-MINT-DATA
│   └── zh-CN/
│       └── (same six files)
├── summaries/
│   ├── en-US/
│   │   └── (six summary files)
│   └── zh-CN/
│       └── (same six files)
├── schemas/
│   ├── mint-components.schema.json
│   └── mint-official-api.schema.json
└── templates/
    ├── MINT-OFFICIAL-API
    └── MINT-COMPONENTS.toml
```

<div style="height: 40px;"></div>

<table align="center">
  <thead>
    <tr>
      <th align="center">Path</th>
      <th align="center">Role</th>
      <th align="center">Normative</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><code>licenses/</code></td>
      <td align="center">License texts, by language</td>
      <td align="center"><strong>Yes</strong></td>
    </tr>
    <tr>
      <td align="center"><code>summaries/</code></td>
      <td align="center">Human-readable summaries</td>
      <td align="center">No</td>
    </tr>
    <tr>
      <td align="center"><code>schemas/</code></td>
      <td align="center">JSON Schema for designation and component files</td>
      <td align="center">Auxiliary</td>
    </tr>
    <tr>
      <td align="center"><code>templates/</code></td>
      <td align="center">Empty templates for adopters</td>
      <td align="center">No</td>
    </tr>
    <tr>
      <td align="center"><code>README.md</code></td>
      <td align="center">Suite documentation</td>
      <td align="center">No</td>
    </tr>
    <tr>
      <td align="center"><code>CHANGELOG.md</code></td>
      <td align="center">Version history</td>
      <td align="center">Auxiliary</td>
    </tr>
  </tbody>
</table>

<p align="center">
When files appear to conflict, the order of authority is: <code>LICENSE-*</code> &gt; <code>CHANGELOG.md</code> (for version identification) &gt; <code>schemas/</code> &gt; <code>summaries/</code> &gt; <code>README.md</code>.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Using MINT in Your Project
</p>

<p align="center" style="font-size: 20px; font-weight: bold;">
  1. Declaring the License
</p>

<p align="center">
Place the base license and the applicable modules in your project. Declare the combination using SPDX identifiers:
</p>

```
SPDX-License-Identifier: LicenseRef-MINT-1.0 AND LicenseRef-MINT-CODE-1.0
```

<p align="center">
Use <code>AND</code> for all combinations, because MINT modules apply cumulatively. <code>OR</code> is not used within the Suite.
</p>

<div style="height: 40px;"></div>

<p align="center" style="font-size: 20px; font-weight: bold;">
  2. Component Mapping
</p>

<p align="center">
A project that distributes products should provide <code>MINT-COMPONENTS.toml</code> at its root. The file declares, for each component, which MINT modules apply. This makes the combination rules objectively executable.
</p>

```toml
[[component]]
path = "engine/"
license = ["LicenseRef-MINT-1.0", "LicenseRef-MINT-CODE-1.0"]

[[component]]
path = "product/glue/"
license = ["LicenseRef-MINT-1.0", "LicenseRef-MINT-CODE-1.0", "LicenseRef-MINT-SOFTWARE-1.0"]

[[component]]
path = "product/ui/"
license = ["LicenseRef-MINT-1.0", "LicenseRef-MINT-DESIGN-1.0", "LicenseRef-MINT-SOFTWARE-1.0"]

[[component]]
path = "product/proprietary/"
license = ["LicenseRef-MINT-1.0", "LicenseRef-MINT-SOFTWARE-1.0"]

[[component]]
path = "api/"
license = ["LicenseRef-MINT-1.0", "LicenseRef-MINT-PUBLIC-1.0"]
```

<p align="center">
The structure is defined by <code>schemas/mint-components.schema.json</code>. The file is strongly recommended for any project that combines more than one module. Without it, a dispute over which component carries which module is resolved against the distributor.
</p>

<div style="height: 40px;"></div>

<p align="center" style="font-size: 20px; font-weight: bold;">
  3. Official API Designation
</p>

<p align="center">
A project that applies the PUBLIC module must designate its official API. The designation is a file named <code>MINT-OFFICIAL-API</code>, placed in the repository root, in another repository, or at a stable URL. The file states its own location and lists the interfaces that constitute the official API.
</p>

```toml
version = "1.0"
location = "repo-path:./api/MINT-OFFICIAL-API"

[[interface]]
name = "example-endpoint"
path = "api/v1/example"
description = "Example interface description."
```

<p align="center">
The structure is defined by <code>schemas/mint-official-api.schema.json</code>. A template is provided at <code>templates/MINT-OFFICIAL-API</code>.
</p>

<p align="center">
If the designation is unreachable, schema-invalid, or lists interfaces the work does not provide, no official API exists for the purposes of PUBLIC. The supersession is cut, and CODE continues to apply. The risk of an invalid designation lies with the copyright holder.
</p>

<div style="height: 40px;"></div>

<p align="center" style="font-size: 20px; font-weight: bold;">
  4. Notice Requirements
</p>

<p align="center">
SOFTWARE and DESIGN require a visible notice. The notice may appear in an "About" screen, in accompanying documentation, or in a license file within the distribution package. It must identify the MINT modules applied and include the disclaimer of warranty.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  How the Licenses Interact
</p>

<table align="center">
  <thead>
    <tr>
      <th align="center">Relationship</th>
      <th align="center">Applies to</th>
      <th align="center">Effect</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">Parallel</td>
      <td align="center">CODE, SOFTWARE, DESIGN, DATA</td>
      <td align="center">Obligations are cumulative; none absorbs another</td>
    </tr>
    <tr>
      <td align="center">Supersession</td>
      <td align="center">PUBLIC over CODE</td>
      <td align="center">For official API access only; lapses on contact with source</td>
    </tr>
    <tr>
      <td align="center">Independence</td>
      <td align="center">Separate works</td>
      <td align="center">Satisfying one work's modules does not satisfy another's</td>
    </tr>
  </tbody>
</table>

<p align="center">
The Suite does not automatically combine with GPL, AGPL, or other strong copyleft licenses. Projects that need to combine MINT with an external license should evaluate compatibility separately. This repository does not provide a compatibility endorsement.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Versioning and Stability
</p>

<p align="center">
Current version: <strong>1.0</strong>. Version numbers follow semantic versioning. A revision that does not change the scope of obligations increments the patch number. A revision that adds obligations or changes the boundary of supersession increments the major number.
</p>

<p align="center">
Each version, once published, is frozen. Historical versions remain available in the repository's releases or tags. Rights granted to recipients under one version are not affected by the publication of a later version.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Copyright and Licensing
</p>

<p align="center">
The license texts in this repository are released under <a href="https://creativecommons.org/publicdomain/zero/1.0/">CC0 1.0 Universal</a>. They enter the public domain. Anyone may copy, modify, distribute, and republish them without attribution, permission, or payment. Anyone may derive new licenses from them, including changing the terms, the name, or the subject matter.
</p>

<p align="center">
CC0 applies to the <strong>license texts themselves</strong>. It does not affect the operation of a MINT license on a work that adopts it. A project that adopts MINT is bound by MINT, not by CC0. CC0 makes the text free to circulate; MINT governs the work that uses it.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Trademarks
</p>

<p align="center">
This repository claims no trademark rights in the name "MINT" or in any MINT identifier. Derived licenses are encouraged to use a different name. If a derived license uses the MINT name, it should state prominently that it is not the official version and has no affiliation with this repository.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Contributing
</p>

<p align="center">
Issues and pull requests are welcome, including reports of ambiguity, boundary cases, compatibility questions, improvements to summaries and schemas, and proposals for new modules. Proposals for new modules should explain how the proposed module differs from the existing five, not merely rename one.
</p>

<p align="center">
Because the license texts are released under CC0, any contribution submitted is deemed to be released under CC0 as well. Substantive changes to the license texts are reviewed by the maintainers and published as a new version. Typographical, formatting, and link corrections may be merged directly.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  Disclaimer
</p>

<p align="center">
The license texts in this repository do not constitute legal advice. The effect of an open source license varies by jurisdiction. Consult a qualified legal professional for questions involving patents, trademarks, export control, or consumer protection.
</p>

<p align="center">
The license texts are provided "as is". The maintainers make no warranty as to their applicability, enforceability, or fitness for a particular scenario.
</p>

<div style="height: 80px;"></div>

<p align="center" style="font-size: 24px; font-weight: bold; letter-spacing: 1px;">
  FAQ
</p>

<p align="center">
<strong>Q: Can I use MINT alone, without any module?</strong><br>
Yes. MINT alone is a permissive license with attribution and a patent grant. It imposes no reciprocity, notice, or share-alike obligation.
</p>

<p align="center">
<strong>Q: Is MINT-CODE-PUBLIC a separate license?</strong><br>
No. It is the combination <code>MINT + CODE + PUBLIC</code>. CODE adds file-level reciprocity; PUBLIC supersedes that reciprocity for official API access. There is no standalone PUBLIC license.
</p>

<p align="center">
<strong>Q: Does PUBLIC supersession last forever?</strong><br>
No. It is behavior-level. It applies only while access is solely through the official API and the user does not copy, modify, or distribute source. Once source is touched, supersession lapses and CODE resumes.
</p>

<p align="center">
<strong>Q: Can I write my own wrapper around the work and claim PUBLIC?</strong><br>
No. Only interfaces designated by the copyright holder as official qualify. A self-written wrapper is governed by CODE.
</p>

<p align="center">
<strong>Q: If I satisfy C's CODE, do I also satisfy A's CODE?</strong><br>
No. Each work's obligations are independent. Satisfying C's modules does not discharge A's modules. The distributor must satisfy both.
</p>

<p align="center">
<strong>Q: Does SOFTWARE absorb CODE?</strong><br>
No. SOFTWARE adds a notice obligation on product distribution. CODE continues to apply to the source files. The obligations are cumulative.
</p>

<p align="center">
<strong>Q: What happens if the official API designation is broken?</strong><br>
The supersession is cut. CODE continues to apply. The risk lies with the copyright holder, not the recipient.
</p>

<p align="center">
<strong>Q: Can I rename MINT and use it for my project?</strong><br>
Yes. The license texts are CC0. Renaming, modifying, and republishing require no permission. A different name is recommended to avoid confusion.
</p>

<p align="center">
<strong>Q: Is MINT compatible with GPL?</strong><br>
Not automatically. MINT-CODE is file-level copyleft, which differs in scope from GPL. Combining MINT with GPL requires separate evaluation. This repository does not provide a compatibility endorsement.
</p>

<p align="center">
<strong>Q: Is component mapping mandatory?</strong><br>
Not for validity. It is strongly recommended for any project that combines more than one module. Without it, a dispute over which component carries which module is resolved against the distributor.
</p>

<div style="height: 80px;"></div>

<p align="center">
<em>This README is released under CC0 1.0.</em>
</p>