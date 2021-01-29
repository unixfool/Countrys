 FILE FORMAT
 ===========

      --------------------------------------------------------------
      All lines beginning with either "" or whitespace are comments
      --------------------------------------------------------------

 IP FROM      IP TO        REGISTRY  ASSIGNED   CTRY CNTRY COUNTRY
 "1346797568","1346801663","ripencc","20010601","IL","ISR","ISRAEL"

 IP FROM   : Numerical representation of IP address.
             Example: (from Right to Left)
             1.2.3.4 = 4 + (3 * 256) + (2 * 256 * 256) + (1 * 256 * 256 * 256)
             is 4 + 768 + 13,1072 + 16,777,216 = 16,909,060

 REGISTRY  : apcnic, arin, lacnic, ripencc and afrinic
             Also included as of April 22, 2005 are the IANA IETF Reserved
             address numbers. These are important since any source claiming
             to be from one of these IPs must be spoofed.

 ASSIGNED  : The date this IP or block was assigned. (In Epoch seconds)
             NOTE: Where the allocation or assignment has been transferred from
                   one registry to another, the date represents the date of first
                   assignment or allocation as received in from the original RIR.
                   It is noted that where records do not show a date of first
                   assignment, the date is given as "0".

 CTRY      : 2 character international country code
             NOTE: ISO 3166 2-letter code of the organisation to which the
             allocation or assignment was made, and the enumerated variances of:
                  AP - non-specific Asia-Pacific location
                  CS - Serbia and Montenegro (Formally Czechoslovakia)
                  YU - Serbia and Montenegro (Formally Yugoslavia) (Being phased out)
                  EU - non-specific European Union location
                  FX - France, Metropolitan
                  PS - Palestinian Territory, Occupied
                  UK - United Kingdom (standard says GB)
                * ZZ - IETF RESERVED address space.

 NOTE: Although CS is not an ISO-3166 code, it appears to be a colloquial term
 used by registries and appears in the RIR (Regional Internet registry) database.

             These values are not defined in ISO 3166 but are widely used.
           * IANA Reserved Address space

 CNTRY     : Country Abbreviation. Usually 3 Character representation

 COUNTRY   : Country Name. Full Country Name.

 ==========
 UPDATE LOG
 ==========

 June 2005    - Countries falling under AFRINIC now show correctly

 October 2006 - Many thanks to Lee Cjin Pheow from Singapore for this:
                As of September 2006, Serbia and Montenegro now have new ISO
                Country codes. See: http://en.wikipedia.org/wiki/Serbia and
                http://en.wikipedia.org/wiki/Montenegro.

                We have updated the database to include "RS" and "ME" for these
                two contries but currently the registries still provide the OLD
                country code data. Thus you may need to translate the codes
                "YU" and "CS" -> "ME" and the same for "ME".

                For the most part it appears that translating CS -> RS and
                YU -> ME works but it is probably not entirely accurate.

 Nov 2006     - Added country code for ÅLAND ISLANDS - AX - ALA
 Mar 2007     - Added Country code for JERSEY - JE - JEY
 Mar 2007     - Added ASCENSION ISLAND - AC (Reserved on request of UPU
                                             Used as a ccTLD)
 ------------------------------------------------------------------------------
 THIS DATABSE IS PROVIDED WITHOUT ANY WARRANTY WHATSOEVER. USE ENTIRELY AT YOUR
 OWN RISK. NO LIABILITY WHATSOEVER, OF ANY NATURE, WILL BE ASSUMEND BY
 Webnet77.com, IT'S DISTRIBUTORS, RESELLERS OR AGENTS. SHOULD THE DATABASE
 PROVE TO BE FAULTY, CAUSE YOU LOSS OR OTHER FINANCIAL DAMAGE, YOU AGREE YOU
 HAVE NO CLAIM AGINST Webnet77.com IT'S DISTRIBUTORS, RESELLERS OR AGENTS. IF
 YOU DO NOT ACCEPT THESE TERMS YOU MAY NOT USE THIS DATABASE.
