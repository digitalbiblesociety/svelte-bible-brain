<script>
import cover_MAT from './41_MAT.jpg'
import cover_MRK from './42_MRK.jpg'
import cover_LUK from './43_LUK.jpg'
import cover_JHN from './44_JHN.jpg'
import cover_ACT from './45_ACT.jpg'
import cover_ROM from './46_ROM.jpg'
import cover_1CO from './47_1CO.jpg'
import cover_2CO from './48_2CO.jpg'
import cover_GAL from './49_GAL.jpg'
import cover_EPH from './50_EPH.jpg'
import cover_PHP from './51_PHP.jpg'
import cover_1TH from './52_1TH.jpg'
import cover_2TH from './53_2TH.jpg'
import cover_COL from './54_COL.jpg'
import cover_1TI from './55_1TI.jpg'
import cover_2TI from './56_2TI.jpg'
import cover_TIT from './57_TIT.jpg'
import cover_PHM from './58_PHM.jpg'
import cover_HEB from './59_HEB.jpg'
import cover_JAS from './60_JAS.jpg'
import cover_1PE from './61_1PE.jpg'
import cover_2PE from './62_2PE.jpg'
import cover_1JN from './63_1JN.jpg'
import cover_2JN from './64_2JN.jpg'
import cover_3JN from './65_3JN.jpg'
import cover_JUD from './66_JUD.jpg'
import cover_REV from './67_REV.jpg'

const options = {
    "MAT": cover_MAT,
    "MRK": cover_MRK,
    "LUK": cover_LUK,
    "JHN": cover_JHN,
    "ACT": cover_ACT,
    "ROM": cover_ROM,
    "1CO": cover_1CO,
    "2CO": cover_2CO,
    "GAL": cover_GAL,
    "EPH": cover_EPH,
    "PHP": cover_PHP,
    "1TH": cover_1TH,
    "2TH": cover_2TH,
    "COL": cover_COL,
    "1TI": cover_1TI,
    "2TI": cover_2TI,
    "TIT": cover_TIT,
    "PHM": cover_PHM,
    "HEB": cover_HEB,
    "JAS": cover_JAS,
    "1PE": cover_1PE,
    "2PE": cover_2PE,
    "1JN": cover_1JN,
    "2JN": cover_2JN,
    "3JN": cover_3JN,
    "JUD": cover_JUD,
    "REV": cover_REV
}

export let book_id = ''

</script>

<img class="w-20 h-20 object-cover rounded object-top" src={options[book_id]} />
