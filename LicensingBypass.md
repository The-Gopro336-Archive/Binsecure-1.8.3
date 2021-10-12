# Bypass
In order to bypass licensing, varible "hashParts" at line 61 in Licenser.kt must be changed.

'''
// line 61	val hashParts = hash.split('.').map { it.toInt() }.toIntArray()
			/**
			 * HashParts value has been changed in order to bypass licensing
			 */
			val hashParts = intArrayOf(
				0x9122,
				0x423,
				0x9219,
				0,
				0x721AB,
				0xFFFF,
				(-0xFFF),
				0x912ED,
				0x91BCD,
				(-0x128D,
				0x99E99,
				0x9812,
			)
'''
