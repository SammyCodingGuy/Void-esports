# Void-esports
```python
@client.event
async def on_member_join(member):
    channel = member.dm_channel
    if channel is None:
        channel = await member.create_dm()
    
    message = (
        "Our pros:\n"
        "https://x.com/m3trol?s=11\n"
        "https://x.com/ultrafv281?s=11\n"
        "https://www.twitch.tv/doxeyfn_?sr=a\n"
        "https://x.com/icyfai?s=21\n"
        "https://x.com/Jaysekbm\n"
        "Our Fortnite tracker:\n"
        "https://fortnitetracker.com/esports/organization/void-esports\n"
        "Void esports is a pro org that is 34th on NAC Fortnite tracker.\n"
        "We are looking for Coaches and Moderators. We look for mature people and our owners are really kind so is everyone in the community.\n"
        "Visit https://voidesports.org/ or\n"
        "Visit https://voidesports.org/teams\n"
        "We have our own merch as well!\n"
        "Visit https://www.voidesports.org/shop\n"
        "We are getting ready for your ticket for when you join..."
    )
    
    await channel.send(message)
``
