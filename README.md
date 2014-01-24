ColorWithHex
============
## A category to get UIColor use HexString

    @interface UIColor (ColorWithHex) 
	+(UIColor*)colorWithHexValue:(uint)hexValue andAlpha:(float)alpha;
	+(UIColor*)colorWithHexString:(NSString *)hexString andAlpha:(float)alpha;
	@end

##  Use

    UIColor *col1 = [UIColor colorWithHexValue:0xFFFFFF andAlpha:1.0];
    //with hash
    UIColor *col2 = [UIColor colorWithHexString:@"#FFFFFF" andAlpha:1.0];

