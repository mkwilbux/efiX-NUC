- [Heading](#heading)
  * [Sub-heading](#sub-heading)
    + [Sub-sub-heading](#sub-sub-heading)
- [Heading](#heading-1)
  * [Sub-heading](#sub-heading-1)
    + [Sub-sub-heading](#sub-sub-heading-1)
- [Heading](#heading-2)
  * [Sub-heading](#sub-heading-2)
    + [Sub-sub-heading](#sub-sub-heading-2)


# Heading levels

> This is a fixture to test heading levels

<!-- toc -->

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading

## Heading

This is an h1 heading

### Sub-heading

This is an h2 heading

#### Sub-sub-heading

This is an h3 heading


# efiX-NUC
EFI suggestions for *X and NUC


## ARCH

For Arch - Depending on the version - Try this:

        Install        archboot media

        Bootloader     gummiboot
       
## Debian

## Unbuntu

Red Hat


SUSE

KALI

Other
       
  As Root:
       
       mount /dev/sdX /mnt
       
       mkdir /mnt/EFI/BOOT
       
       cp /mnt/EFI/DISTROName/* /mnt/EFI/BOOT
       
       mv /mnt/EFI/BOOT/grubx64.efi /mnt/EFI/BOOT/bootx64.efi
      
       
## Alternately, go old school

        use lilo :D
       
