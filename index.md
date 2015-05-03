|LR_metadata field name| Metadata search bar field name | Source | Text search bar field name | Text search dropdown subset | Smart collection field name|
|---|---|---|---|---|---|
|caption|||Caption|Self < ASF|?|
|file path||||ASF|?|
|virtual copy name|||Copy Name|Self < ASF|?|
|keywords|Keyword||Keywords|Self < ASF|?|
|collection name||||ASF|?|
|filename|||Filename|Self|?|
|copy name <sup>[1](#myfootnote1)</sup>|||Copy Name|Self|?|
|make||EXIF||Searchable EXIF|?|
|model|Camera|EXIF||Searchable EXIF|?|
|serial number|Camera Serial Number|EXIF||Searchable EXIF|?|
|software||EXIF||Searchable EXIF|?|
|job title||IPTC:Contact||Searchable IPTC|?|
|address||IPTC:Contact||Searchable IPTC|?|
|city||IPTC:Contact|N/A|Searchable IPTC|?|
|state/province||IPTC:Contact|N/A|Searchable IPTC|?|
|postal Code||IPTC:Contact|N/A|Searchable IPTC|?|
|country||IPTC:Contact|N/A|Searchable IPTC|?|
|creator|Creator|IPTC:Contact|N/A|Searchable IPTC|?|
|headline||IPTC:Content<sup>[2](#myfootnote2)</sup>|N/A|Searchable IPTC|?|
|IPTC subject code||IPTC:Content<sup>[2](#myfootnote2)</sup>|N/A|Searchable IPTC|?|
|description writer||IPTC:Content<sup>[2](#myfootnote2)</sup>|N/A|Searchable IPTC|?|
|intellectual genre||IPTC:Image Description|N/A|Searchable IPTC|?|
|IPTC Scene Code||IPTC:Image Description|N/A|Searchable IPTC|?|
|sublocation|Sublocation|IPTC:Image Description|N/A|Searchable IPTC|?|
|city|City|IPTC:Image Description|N/A|Searchable IPTC|?|
|state/province|State / Province|IPTC:Image Description|N/A|Searchable IPTC|?|
|country|Country|IPTC:Image Description|N/A|Searchable IPTC|?|
|ISO Country Code||IPTC:Image Description|N/A|Searchable IPTC|?|
|job identifier|Job|IPTC:Status<sup>[3](#myfootnote3)</sup>|N/A|Searchable IPTC|?|
|instructions||IPTC:Status<sup>[3](#myfootnote3)</sup>|N/A|Searchable IPTC|?|
|creditline||IPTC:Status<sup>[3](#myfootnote3)</sup>|N/A|Searchable IPTC|?|
|source||IPTC:Status<sup>[3](#myfootnote3)</sup>|N/A|Searchable IPTC|?|
|title|Title|IPTC:Status<sup>[3](#myfootnote3)</sup>|Title|Self < SM, Searchable IPTC|?|
|rights usage terms||IPTC:Copyright|N/A|Searchable IPTC|?|
|copyright info URL||IPTC:Copyright|N/A|Searchable IPTC|?|

<a name="myfootnote1">1</a>: Virtual copy names are referred to as either simple "Copy Name" or "Virtual Copy Name"

<a name="myfootnote2">2</a>: Windows and OS X use different names: Content (Mac OS) / IPTC (Windows)

<a name="myfootnote3">3</a>: Windows and OS X use different names: IPTC Status (Mac OS) / Workflow (Windows)

<a href="https://helpx.adobe.com/lightroom/help/finding-photos-catalog.html">Adobe documentation</a> ambiguously refers to both <code>IPTC:Image Description:City</code>, and <code>IPTC:Contact:City</code>.<br/>The metadata search bar refers to <code>IPTC:Image Description:City</code>.

<a href="https://helpx.adobe.com/lightroom/help/finding-photos-catalog.html">Adobe documentation</a> ambiguously refers to both <code>IPTC:Image Description:State/Province</code>, and <code>IPTC:Contact:State/Province</code>. <br/>The metadata search bar refers to <code>IPTC:Image Description:State</code>.

<a href="https://helpx.adobe.com/lightroom/help/finding-photos-catalog.html">Adobe documentation</a> ambiguously refers to both <code>IPTC:Image Description:Country</code>, and <code>IPTC:Contact:Country</code>.<br/>The metadata search bar refers to <code>IPTC:Image Description:Country</code>.

<a href="https://helpx.adobe.com/lightroom/help/finding-photos-catalog.html">Adobe documentation</a> ambiguously refers to both <code>IPTC:Status:Job Identifier</code>, and <code>IPTC:Contact:Job Title</code>.<br/>The metadata search bar refers to <code>IPTC:Status:Job Identifier</code>.
