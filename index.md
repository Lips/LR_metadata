
|LR_metadata field name| Metadata search bar field name | Source | Text search bar field name | Text search dropdown subset | Smart collection field name|
|---|---|---|---|---|---|
|caption||IPTC Content:Description|Caption|Self < ASF|Caption|
|file path||||ASF|~Folder|
|keywords|Keyword|IPTC Content:Keywords|Keywords|Self < ASF|Keywords|
|collection name||||ASF|Collection|
|filename|||Filename|Self|Filename|
|virtual copy name <sup>[1](#myfootnote1)</sup>||LR:File/Folder|Copy Name|Self < ASF|Copy Name|
|make||EXIF||Searchable EXIF|---|
|model|Camera|EXIF||Searchable EXIF|Camera|
|serial number|Camera Serial Number|EXIF||Searchable EXIF|Camera Serial Number|
|software||EXIF||Searchable EXIF|?|
|job title||IPTC:Contact||Searchable IPTC|?|
|address||IPTC:Contact||Searchable IPTC|?|
|city||IPTC:Contact||Searchable IPTC|?|
|state/province||IPTC:Contact||Searchable IPTC|?|
|postal Code||IPTC:Contact||Searchable IPTC|?|
|country||IPTC:Contact||Searchable IPTC|?|
|creator|Creator|IPTC:Contact||Searchable IPTC|?|
|headline||IPTC:Content<sup>[2](#myfootnote2)</sup>||Searchable IPTC|?|
|IPTC subject code||IPTC:Content<sup>[2](#myfootnote2)</sup>||Searchable IPTC|?|
|description writer||IPTC:Content<sup>[2](#myfootnote2)</sup>||Searchable IPTC|?|
|intellectual genre||IPTC:Image Description||Searchable IPTC|?|
|IPTC Scene Code||IPTC:Image Description||Searchable IPTC|?|
|sublocation|Sublocation|IPTC:Image Description||Searchable IPTC|?|
|city|City|IPTC:Image Description||Searchable IPTC|?|
|state/province|State / Province|IPTC:Image Description||Searchable IPTC|?|
|country|Country|IPTC:Image Description||Searchable IPTC|?|
|ISO Country Code||IPTC:Image Description||Searchable IPTC|?|
|job identifier|Job|IPTC:Status<sup>[3](#myfootnote3)</sup>||Searchable IPTC|?|
|instructions||IPTC:Status<sup>[3](#myfootnote3)</sup>||Searchable IPTC|?|
|creditline||IPTC:Status<sup>[3](#myfootnote3)</sup>||Searchable IPTC|?|
|source||IPTC:Status<sup>[3](#myfootnote3)</sup>||Searchable IPTC|?|
|title||IPTC:Status<sup>[3](#myfootnote3)</sup>|Title|Self < SM, Searchable IPTC|Title|
|rights usage terms||IPTC:Copyright||Searchable IPTC|?|
|copyright info URL||IPTC:Copyright||Searchable IPTC|?|

<a name="myfootnote1">1</a>: Virtual copy names are referred to as either simple "Copy Name" or "Virtual Copy Name"

<a name="myfootnote2">2</a>: Windows and OS X use different names: Content (Mac OS) / IPTC (Windows)

<a name="myfootnote3">3</a>: Windows and OS X use different names: IPTC Status (Mac OS) / Workflow (Windows)

<a href="https://helpx.adobe.com/lightroom/help/finding-photos-catalog.html">Adobe documentation</a> ambiguously refers to both <code>IPTC:Image Description:City</code>, and <code>IPTC:Contact:City</code>.<br/>The metadata search bar refers to <code>IPTC:Image Description:City</code>.

<a href="https://helpx.adobe.com/lightroom/help/finding-photos-catalog.html">Adobe documentation</a> ambiguously refers to both <code>IPTC:Image Description:State/Province</code>, and <code>IPTC:Contact:State/Province</code>. <br/>The metadata search bar refers to <code>IPTC:Image Description:State</code>.

<a href="https://helpx.adobe.com/lightroom/help/finding-photos-catalog.html">Adobe documentation</a> ambiguously refers to both <code>IPTC:Image Description:Country</code>, and <code>IPTC:Contact:Country</code>.<br/>The metadata search bar refers to <code>IPTC:Image Description:Country</code>.

<a href="https://helpx.adobe.com/lightroom/help/finding-photos-catalog.html">Adobe documentation</a> ambiguously refers to both <code>IPTC:Status:Job Identifier</code>, and <code>IPTC:Contact:Job Title</code>.<br/>The metadata search bar refers to <code>IPTC:Status:Job Identifier</code>.
