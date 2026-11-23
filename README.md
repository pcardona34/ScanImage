# ScanImage

##  What is ScanImage

It is a GNUstep application to proceed scan work.

## Credits

This repo was forked from the native Application created by Ondrej Florian within its [GSDE](https://github.com/onflapp/gnustep-desktop) project.

## Localization

- English (by default)
- French

## How to install

### With agnostep-apps-manager

1. Run [Agnostep Apps Manager](../../../agnostep-apps-manager).
2. Select the category: `gnustep-utilities`
3. Select the application: `ScanImage`
4. Read App Info.
5. Confirm installation.

### By yourself

**Dependencies**:

- You need scan libs.

> [!NOTE]
> These frameworks are avaible from GSDE.
> Otherwise, they are also installed within [agnostep-desktop](../../../agnostep-desktop), and seemingly within [Nextspace](https://github.com/trunkmaster/nextspace).

Then execute:

```console
make
sudo -E make install
```

## Using

```console
openapp ScanImage &
```

Or use the app icon from the `Applications` folder.
