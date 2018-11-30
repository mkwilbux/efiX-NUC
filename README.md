<!--MarkdownTOC levels ="2,3" autolink="true" style="ordered"-->

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
       
