Title: Proposal to Add Asia/Penampang to the IANA Time Zone Database

Submitted by:
Denis Martin
Penampang, Sabah, Malaysia
penampang.tzproposal@fakemail.org

Summary:
This document proposes the addition of a new time zone entry to the IANA Time Zone Database: Asia/Penampang. This proposed zone would represent Penampang and the greater Kota Kinabalu region in the state of Sabah, East Malaysia.
Although it would share the same UTC offset (+08:00) as existing zones like Asia/Kuala_Lumpur and Asia/Kuching, the historical and civil context of Sabah justifies its inclusion as a distinct time zone identifier.

Rationale:
    1. Historical Time Zone Distinction:
        ◦ Prior to 1982, Malaysia operated with two separate time zones:
            ▪ West Malaysia (Peninsular): UTC+07:30
            ▪ East Malaysia (Sabah & Sarawak): UTC+08:00
        ◦ In 1982, the Malaysian government unified the time zones under UTC+08:00 nationwide. While this change brought West Malaysia ahead of its solar time, it was naturally aligned with Sabah's geographic solar noon.
    2. Geographical and Civil Uniqueness:
        ◦ Sabah is geographically located on the island of Borneo, significantly east of Kuala Lumpur.
        ◦ The city of Penampang, bordering the state capital Kota Kinabalu, serves as a cultural center of the Kadazan-Dusun community.
        ◦ Sabah and Sarawak were distinct entities under the Malaysia Agreement 1963 and retain significant administrative autonomy.
        ◦ IANA precedent allows multiple zones with identical UTC offsets when historical or administrative distinctions exist (e.g., Asia/Jakarta, Asia/Makassar; Australia/Sydney, Australia/Melbourne).
    3. Cultural Recognition and Technical Use:
        ◦ Acknowledging Asia/Penampang enhances localization and regional awareness for users in Sabah.
        ◦ Software applications, scheduling systems, and international tools benefit from greater regional accuracy.
        ◦ This follows a similar rationale as Asia/Kuching (for Sarawak), despite identical UTC offsets.

Proposed Zone Entry:
Zone Asia/Penampang    8:00    -    MYT
Optionally, a compatibility link could be added:
Link Asia/Penampang    Asia/Kota_Kinabalu

References:
    • Malaysia Time Act 1951 (Act 261) and subsequent amendments.
    • Malaysia Agreement 1963 (MA63)
    • Public records and government statements regarding the 1982 unification of Malaysian time zones.
    • Precedents in tzdata for regions with distinct identity despite shared UTC offsets.

Conclusion:
This proposal respectfully requests the inclusion of Asia/Penampang in the IANA Time Zone Database to better represent the unique history, geography, and cultural identity of Sabah, Malaysia. The addition is technically non-disruptive, legally consistent, and culturally meaningful.
We appreciate your consideration and are available for any further discussion.

Contact:
Denis Martin
Sabah Time Zone Advocacy
penampang.tzproposal@fakemail.org
