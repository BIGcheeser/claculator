import discord
from discord.ext import commands
import os

Bot = commands.Bot(command_prefix = '.')

@Bot.event
async def on_ready():
    print('bot is ready')
    
@Bot.command()
async def add(ctx,a:int,b:int):
    await ctx.send(a+b)

@Bot.command()
async def sub(ctx,a:int,b:int):
    await ctx.send(a-b)

@Bot.command()
async def multiply(ctx,a:int,b:int):
    await ctx.send(a*b)

@Bot.command()
async def divide(ctx,a:int,b:int):
    await ctx.send(a/b)
    
Bot.run('token')
